硬广植入：本人自己搭建了个git代码托管服务器，各位大佬可以在我的git服务器里建立免费的私有库，也可以作为备用代码储存点，毕竟github总是会出问题的，本git服务器架设在华为云的广州节点上，git代码托管地址如下：
http://gayhub.fun (ps.本人不是基佬)

---



# 项目简介
本项目是我个人网站[Alpaca Bi的个人博客](https://biguokang.cn)的后台server源码，基于node.js开发，使用了express框架，该项目目前依然在维护中。想看本项目完整效果，可以访问我的个人网站

# 安装与使用方法

### mysql安装
由于本项目使用了mysql作为数据库，最好配置好了数据库和对于的表结构才开始部署安装后台server，至于如何配置我不告诉你（开玩笑的等我有空再更新）


### 安装过程
1. 在你的项目目录下，使用`git clone https://github.com/biguokang/bgk-blog-server.git `命令
2. 下载完成后，进入目录，输入`npm install`命令
3. 之后输入`node server.js`，server服务器就跑起来了！！！

### 注意事项
- 本项目只是单纯的后台server，需要搭配前台界面和后台界面使用才能看出效果，[点击这里](https://github.com/biguokang/bgk_blog_css)可以下载和部署前台代码
- 本项目默认端口为8888


# 本后台项目所用到的技术和工具
- 开发语言：JavaScript和ES6标准
- 运行平台：node.js
- 框架：express
- 用户验证：cookie-session
- 数据库：mysql
- POST文件处理：multer
- MD5签名工具：node-forge
- 反向代理工具：nginx（线上环境）
- 服务器：阿里云华南节点