---
title: New Computer
date: 2019-05-08 15:12:24
tags:
---
---
安装软件

<!-- more -->

## 一、安装软件
1. 安装浏览器：谷歌、火狐、360极速
2. 安装2345看图王（方便查看jpg/png/pdf）
3. 安装git  node npm sass
~~~
    git --version   查看git是否安装成功    
    
    node 配置环境变量
    
    1、PATH上增加node.exe的目录D:\\nodejs（目录根据实际情况更改）
    2、增加环境变量NODE_PATH,值为D:\\nodejs\\node_modules
    
    node -v           查看node是否安装成功
    npm install -g cnpm  安装淘宝镜像cnpm
    cnpm install -g node-sass
    node-sass -v
    node-sass -w index.scss index.css
    node-sass  -w  index.scss  index.css  --output-style  expanded   //sass 监听
~~~

4. 安装编辑器：webstrom和sublime
	win [sublime](https://download.sublimetext.com/Sublime%20Text%20Build%203143%20x64%20Setup.exe)
    webstorm2017.1激活方式 亲测有效
~~~
 注册时，在打开的License Activation窗口中选择“License server”，然后输入下面的网址：
    http://idea.iteblog.com/key.php
    或者：
    http://idea.imsxm.com/
~~~
[汉化](http://www.cnblogs.com/lvyueyang/p/6835470.html)
5. 安装JDK 、tomcat
~~~
	配置环境变量
   		 tomcat
    	1、PATH 上增加  D:\tomcat\apache-tomcat-9.0.2\bin
    	2、增加环境变量 CATALINA_HOME  及 D:\tomcat\apache-tomcat-9.0.2
         JDK
    	1、PATH 上增加  D:\Program Files\Java\jdk1.8.0_151\bin
    	2、增加环境变量 JAVA_HOME  及 D:\Program Files\Java\jdk1.8.0_151
        
        点击tomcat  bin文件夹下面的 startup.bat
        下图表示启动成功:  
~~~
:-: ![](images/微信截图_20180110163036.png)

附：配置环境变量的图
:-: ![](images/微信截图_20180110161115.png)

:-: ![](images/微信截图_20180111101242.png)


6、安装吸色软件 Faststone Capture
激活
~~~
	name：bluman
　　serial/序列号/注册码：VPISCJULXUFGDDXYAUYF
~~~