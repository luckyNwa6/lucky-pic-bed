# 图床安装

先创建一个仓库，记得是公开的加勾选 md 文档，再去https://github.com/settings/apps

可以看到 Personal access tokens 点开，点 Tokens 再点 New personal access token (classic)，时间永久过期，勾选 repo 再生成，然后保存一下 token 等会要用

## picGo

下载并启用，如果不能启动，右键勾起兼容模式，管理员身份启动

设置如下
![图片](https://cdn.jsdelivr.net/gh/luckyNwa6/lucky-pic-bed@main/img/20240630112936.png)

**注意**

设定自定义域名下面带加速的：

https://cdn.jsdelivr.net/gh/[github用户名]/[仓库名]@main

注意，此处的分支一定要填写@main，否则默认使用 master 分支。而现在 github 创建的默认分支名为 main，如果不指定，则会出现图片不能上传的情况

picgo-server 设置里端口必须在 PicGo 设置中--->设置 Server---> 36677

GitHub 图床仓库大小不能超过 1G。因为 GitHub 原则上是反对仓库图床化的，当仓库超过 1G 后会有人工审核仓库内容，如果发现用来做图床，轻则删库重则封号

## Typora

绑定 Typora，在顶部菜单界面，选择“文件” - > “偏好设置”，设置图片存储方式

## 使用

更新 npm 图床务必要记得更新 package.json 里的版本号！
