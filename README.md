### GIT第二天

#####本地和远程仓库相关联

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
git push -u origin master
```

##### HTTPS协议和SSH协议的区别

- HTTPS协议