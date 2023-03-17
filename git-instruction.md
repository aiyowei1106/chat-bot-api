## Git 常用命令
```
Git详细教程：https://juejin.cn/post/6844903494617399309#heading-39
```
### 操作命令
```
初始化本地仓库：
    git init
```
```
关联远程仓库：
    git remote add origin https://github.com/XXX.git/
```
```
文件添加到暂存区：
    git add .
    【后面的小数点“.”，意为添加文件夹下的所有文件】
```
```
文件提交到仓库：
    git commit -m "提交说明"
```
```
获取远程库与本地同步合并：
    git pull --rebase origin master
    【如果远程库不为空必须做这一步，否则后面的提交会失败】
```
```
推送到远程仓库：
    git push -u origin master
```

### 用户名/邮箱/密码
```
查看用户名：
    git config user.name
```
```
查看密码：
    git config user.password
```
```
查看邮箱：
    git config user.email
```
```
设置用户名：
    git config --global user.name "xxxx名称"
    【--global：全局设置】
```
```
设置密码：
    git config --global user.password "xxxxx密码"
```
```
设置邮箱：
    git config --global user.email "xxxx.com邮箱"
```
```
查看已设配置：
    git config --list
```