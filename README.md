# git

## How to Push Commit
```
git status
git add .
git commit -m "ANY COMMENT"
git push origin master
```

## Delete All Old Commits

```
git checkout --orphan new_branch
git add -A
git commit -am "First Commit"
git branch -D master
git branch -m master
git push -f origin master
```
