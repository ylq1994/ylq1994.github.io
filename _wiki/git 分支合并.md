---
layout: wiki
title: Git 分支合并
categories: Git
description: Git。
keywords: Git
---

**目录**

* TOC
{:toc}

## 查看分支
1. 查看本地分支：
```
    $ git branch
```
2. 查看远程分支：
```
    $ git branch -r
```

## 创建分支
```
    本地分支
    $ git branch [name] ----注意新分支创建后不会自动切换为当前分支

    创建远程分支(本地分支push到远程)：$ git push origin [name]
```
## 切换分支
```
    切换分支
    $ git checkout [name]

    创建新分支并立即切换到新分支：
    $ git checkout -b [name]
```
## 删除分支
```
    $ git branch -d [name] ---- -d选项只能删除已经参与了合并的分支，对于未有合并的分支是无法删除的。如果想强制删除一个分支，可以使用-D选项

    删除远程分支：$ git push origin :heads/[name]
```
## 合并分支
> 合并到哪个分支 要先切换到对应的分支(例如要合并到主分支，要先执行 $ git checkout master)
```
    合并分支：
    $ git merge [name] ----将名称为[name]的分支与当前分支合并
```