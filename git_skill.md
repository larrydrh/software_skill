## git skill

### 分支管理
```
git checkout -b local_branch  remote_branch
git branch -d/D local_branch
git checkout -b feacher remote_branch
git merge --no-ff feacher
```

### 如何管理一个分支上的多个提交
```
git rebase [commit-id]
git add .
git commit --rebase
git rebase --continue
```

### 如何将一个分支上的提交制作成patch
```
git format-patch -1
git apply --check 0001xxx.patch
git am 0001xxx.patch
```

### 如何查看log
```
git log
TODO
```
