If you make a commit with an email address of the form:
```
ID+USERNAME@users.noreply.github.com
```

where *you can choose any ID you want*, then Github will associate that commit with
the user who actually owns that ID!

E.g. user `ashtom` has ID 70720 according to https://api.github.com/users/ashtom. So I did:
```bash
git config --local user.email '70720+obviouslyfake@users.noreply.github.com'
```

Then made a commit and pushed...
