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