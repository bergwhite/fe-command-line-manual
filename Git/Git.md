# Git 手册

## 基础

```

git init  // 初始化当前项目为Git仓库
git remote add v url  // 添加远程仓库v，地址为url
git pull v master  // 拉取远程仓库v的master分支到本地
git add *  // 添加所有文件
git status  // 查看当前的状态
git commit -m 'someinfo'  // 提交到仓库
git push v master  // 推送到远程仓库v的master分支

```

## 标签

```

git tags  // 列出标签
git pull origin --tags  // 拉取最新标签
git push origin --tags  // 推送标签
git branch -D test  // 删除分支

```

## 分支

```

git checkout -b test  // 创建并切换到test分支
git checkout master  // 切换到master分支

```

## 合并

```

git merge dev  // 把dev合并到master下

```

## 删除

```

git branch -D br  // 删除本地分支
git push origin :br  (origin 后面有空格)  // 删除远程分支

```

## 回滚

```

git reset --hard commit-id  /回滚到commit-id，讲commit-id之后提交的commit都去除
git reset --hard HEAD~3  // 将最近3次的提交回滚

```

## 修改

```

git commit --amend -m ''  // 修改刚在本地提交的commit

```