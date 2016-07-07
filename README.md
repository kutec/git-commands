#Git Commands
---
## Deleting a branch

**Local branch**
```
git branch <branchName> -d
```
**Remote branch**
```
git push origin --delete <branchName>
```

## Force Git PULL
```
git fetch origin master
git reset --hard FETCH_HEAD
git clean -df
```
