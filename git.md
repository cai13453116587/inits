> git 是什么？ svn

- 版本管理工具


git 是一个分布式的管理工具

svn 是一个集中式的管理工具



本地文件夹（工作区） -》 暂存区 =》 历史区（产生提交记录）


```
//工作区=》暂存区
    git add filename/dirpath/.当前文件夹
```
```
//暂存区=》历史记录
git commit -m "提交信息"

```



```
git log 查看提交记录

```

```
// 查看git本地用户
git config --list

```

```
//配置用户
git config --global user.name "用户名"
git config --global user.email "邮箱"
```


```
//查看工作区状态变化
git status
```

```
//查看工作区和暂存区的区别
git diff
```

```
//回到上一次操作
git reset "HEAD^"  有几个^ 就退几层
```

```
// 撤销
git checkout 文件名
```

```
本地文件跟远程仓库关联
git remote add origin "仓库地址"
```