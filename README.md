### GIT第二天

#####本地和远程仓库相关联(推荐在项目已经开始的时候使用)

```
#在项目目录下新建一个文件(建议是README.md)
git init
git add 文件名 或 git add .文件上传暂存区
git commit -m "注释" 上传仓库
#git remote add 这一步是做关联，地址写自己仓库地址，只写一次
#HTTP配置
git remote add origin https://github.com/z1021003215/1021003215.git
#ssh配置
git remote add origin https://github.com/z1021003215/1021003215.git
#推送到网络仓库,-u
git push -u origin master
```

##### HTTPS协议和SSH协议的区别

- HTTPS协议-提交的时候会验证用户信息（验人）
- SSH协议-需要进行配置，配置好后不会有验证弹窗(验机器)

#### SSH的配置

##### 生成key

​	