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

## Create a New and Empty Branch in Git
```
git checkout --orphan <branchname>
git rm -rf . //will remove all unstaged folders and files
```

## Switching Directories
```
git checkout master
git checkout <branchname>
```
