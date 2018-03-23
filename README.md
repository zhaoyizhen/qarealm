**编写目的**
 这个自己尝试搭建的第一网站：http://qarealm.com <br>
 开发语言选择的PHP。因为现在很多网站采用的是PHP，比较成熟。<br>
 自己对PHP不熟悉使用了WorkPress来搭建自己的网站。<br>
 这个是用来记录自己搭建网站的过程。
***
**域名和云服务器**
 在腾讯云使用微信登录，注册后购买了域名qarealm.com。<br>
 腾讯云服务器在做活动，购买了一台“1核 1GB 1Mbps”的云服务器。<br>
 云服务器预装“Cent OS 7”系统。<br>
 先重置云服务器的登录密码。“控制台”→“云服务器”→勾选后“重置密码”。<br>
 登录云服务器。腾讯云服务器可以直接点击“登录”在浏览器中直接打开服务器。
***
**安装wdcp**
 先安装了wdcp,安装参照：http://www.wdlinux.cn/wdcp/ 官方网站<br>
 我使用源码安装的方式，命令如下：<br>
 wget http://dl.wdlinux.cn/lanmp_laster.tar.gz<br>
 tar zxvf lanmp_laster.tar.gz<br>
 sh lanmp.sh<br>
 选择的3，安装N+A的引擎组合。
***
**配置wdcp**
 安装成功之后 在浏览器输入你的 IP:8080 就可以登录后台了。<br>
 默认的登录用户名是admin 密码是 wdlinux.cn
