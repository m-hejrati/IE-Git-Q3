# IE-Git-Q3
Internet Engineering - Git Assignment - AUT

### First Part
We can use `git commit --amend` to modify the most recent commit.

### Second Part
Below command can help us to permanently remove a file from git repository and history.
```
git filter-branch --index-filter "git rm -rf --cached --ignore-unmatch part2.env" HEAD
git push origin --force
```

### third Part
we need to create a new branch with `git branch NAME`

### fourth part
choose a commit and merge it with below command.

```
git cherry-pick beea429
```
