# git命令

## 回滚到某个commit

```
> git reset --hard <commit_id>
> git push origin <branch_name> --force
```

## 撤回commit 

`git reset —mixed <commit_id>`

## 分支更换名称

`git branch -m 原名 新名`

## 删除本地分支

`git branch -r -d origin/xxxx`