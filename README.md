# WordPress-webstack-pro
webstack-pro网址导航网站

我做的是一个AI导航站，网址导航，想的是现在市场上AI软件越来越多种类，做个细分，能让用户快速导航到想去的官网，避免广告啊浏览器排名啊啥的骚扰。

一.需要的准备
1.域名，域名可以在腾讯云，阿里云去购买，一年才30多

2.服务器，现在很多活动，基础新人版的服务器不需要太好，2g内存就够了，反正最低配就行了，后期网站如果流量做起来了再升级也不迟。

有了这两个部分，基本就没啥问题了

接下来就是域名备案，备案性质看你自己的经营范围，反正我是个人性质备案，个人博客类网站，做的是网址导航。

备案一般来说提交后3天内阿里云初审，阿里云会通过电话询问方式审核，就是确认你的网站性质，个人身份，很简单，就通过了。

阿里云初审后，就是工信部审核。一般来说也是3天左右（工作日）

二.服务器搭建环境
我选的是Windows环境，因为我只熟悉这个，哈哈

Windows服务器你可以在里面安装宝塔软件，这个对于新手或者运维来说非常友好。

1.宝塔环境
![image](https://github.com/user-attachments/assets/11e24662-9c5e-40a6-8fc0-d1a9ec893982)


对于新手来说，使用宝塔来搭建环境是非常方便的，这里直接在左侧的侧边栏找到软件商店
![image](https://github.com/user-attachments/assets/9069ec91-17cf-4ec4-b411-488cac556026)



这里可以直接一键部署WordPress，他这里好就好在，一键部署的时候，他会把你的运行环境也给你搭建好。

缺PHP环境，就一键部署，缺Mysql环境，也可以一键部署。

mysql最好别装最新版，MySQL8.0与MySQL5.0所采用的加密方式规则不一样

这样会导致可视化界面软件，比如Navicat啥的无法连接，没必要整那么麻烦。

php和的环境搭建网上有非常多的教程，这里就不细说了

如何安装和配置PHP开发环境？_安装php环境-CSDN博客
https://blog.csdn.net/m0_74824661/article/details/144015977

![image](https://github.com/user-attachments/assets/1bc882d3-3b54-4a50-87a5-c2275bd5ad57)



2.WordPress
当你php，mysql，apache都安装好了，就可以开始搭建WordPress了

WordPress如果你使用宝塔一键部署，就会直接进入到经典的5分钟构建环节

![image](https://github.com/user-attachments/assets/f3aa007d-665c-412f-8218-4dc47d3fb2fa)


也可以在官网上下载WordPress

下载 – WordPress.org China 简体中文
https://cn.wordpress.org/download/

当你五分钟的安装流程走完后，

就会来到仪表盘的界面。

![image](https://github.com/user-attachments/assets/807abfbc-9701-4ac0-b141-e74bf963718a)


这里可以在左侧选择主题设置，上传主题，现在市面上非常多WordPress的主题可以供你选择，

比如电商类的，网址导航类的，作品集，外贸啥的，很多模板。

这里我选择的是webstack pro

webstack是开源的

webstack · GitHub Topics · GitHub

pro版的话网上很多资源

webstack pro主题下载
https://www.123gpt.cn/sites/webstack-pro%e4%b8%bb%e9%a2%98%e5%85%8d%e8%b4%b9%e4%b8%8b%e8%bd%bd-123gpt-ai%e5%af%bc%e8%88%aa.html

下载好主题后就可以在后台导入了，

导入后的效果就是这样的

![image](https://github.com/user-attachments/assets/bd7af68f-f6f9-4deb-aaf9-e040495b3409)


你可以在里面去设置首页，主题，颜色，内容，等等一系列功能

这里发布内容项也很简单，首先创建菜单

WordPress导航菜单教程|自定义菜单【图文教程】 - WordPress外贸建站专家
https://www.wppop.com/wordpress-menu-tutorials.html

然后添加网址，填完相关网址信息后，勾选右侧放到哪里
![image](https://github.com/user-attachments/assets/bc385784-1fad-4265-af91-0cd95dd9714d)



然后点击发布。

前端数据就立马会出现了。

![image](https://github.com/user-attachments/assets/f883e231-dce5-4c4d-81ce-88c953ed70be)


这里webstack pro天气插件我这边有点bug，前端调试到耗费10s加载天气插件，于是我在后台果断关闭了。

网址导航详细页里有该对应网址的二维码链接，

WordPress主题里还有个二维码api设置


这里他会自动将你指定网站的链接转成二维码。

我这里用api是https://my.tv.sohu.com/user/a/wvideo/getQRCode.do?width=$size&height=$size&text=$url

如有不懂的欢迎+v  Goodbye_cq 备注来意
