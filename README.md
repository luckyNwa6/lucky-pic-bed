# 图床安装教程

先创建一个仓库，记得是公开的加勾选md文档，再去https://github.com/settings/apps

可以看到 Personal access tokens 点开，点 Tokens 再点New personal access token (classic)，时间永久过期，勾选repo再生成，然后保存一下 token 等会要用

## picGo
下载并启用，如果不能启动，右键勾起兼容模式，管理员身份启动

设置如下
![图片](https://cdn.jsdelivr.net/gh/luckyNwa6/lucky-pic-bed@main/img/20240630112936.png)

**注意** 

设定自定义域名下面带加速的：

https://cdn.jsdelivr.net/gh/[github用户名]/[仓库名]@main

注意，此处的分支一定要填写@main，否则默认使用master分支。而现在github创建的默认分支名为main，如果不指定，则会出现图片不能上传的情况

picgo-server 设置里端口必须在PicGo设置中--->设置Server---> 36677 

## Typora
绑定Typora，在顶部菜单界面，选择“文件” - > “偏好设置”，设置图片存储方式
