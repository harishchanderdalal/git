# git

## How to delete all the old Commit

```
git checkout --orphan new_branch
git add -A
git commit -am "First Commit"
git branch -D master
git branch -m master
git push -f origin master
```
