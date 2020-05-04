## 楚门的世界（Heroku Node Unblocker）

### 使用方法（简易版）

1. Fork 项目<br>
在当前页面点击右上角的 Fork 将项目拷贝至自己的 Github 账号下。<br>
2. <a href="https://dashboard.heroku.com/apps">登录自己的 Heroku 帐号。</a><br>
3. 新建 app<br>
在 heroku 控制台页面点击 右上角的 New 新建一个 app, app 名称将作为网站域名。<br>
4. 关联 Github<br>
创建完 app 后点击 app 进入 app 管理页面, 然后点击 Deploy(默认创建后跳转到这个页面)。<br>
点击页面中的 GitHub/Connect to Github, 会要求你登录 Github, 请登录刚刚 Fork 项目的 Github账号。<br>
5. 部署<br>
当前页面将会显示你关联的 Github 账号, 在 Search for a repository to connect to 选项中输入 web-proxy-heroku
并点击 Search, 选择 repo 点击 Connect, 连接完成后, 在最下方点击 Deploy Branch 完成部署。<br>

### 关于

原项目地址: https://github.com/nfriedly/node-unblocker
<br>
有位作者进行了修改以适合 heroku 部署: https://github.com/gfw-breaker/heroku-node-proxy
<br>
本项目基于修改版的基础上，仅仅是修改了主页。
