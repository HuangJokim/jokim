# selenium+python 初步学习

## 安装

安装3.7版本python 



用pip3 install selenium 

安装最新版本selenium 



pycharm 破解方式：<https://blog.csdn.net/thomas0713/article/details/82927934> 



火狐版本：<http://ftp.mozilla.org/pub/mozilla.org//firefox/releases/> 

（最新版本下载） 

整体的环境搭建：<https://www.jianshu.com/p/2f2363f4d133> 



安装火狐驱动：<https://blog.csdn.net/cn7311/article/details/75453261> 

安装chrome最新版本

安装chrome对应的驱动

装完之后，pycharm需要重启打开 

### 测试是否安装成功

代码： 

from selenium import webdriver 



import time 



driver = webdriver.Firefox() 



driver.get('<http://www.baidu.com>') 



print ("You can search anything you want via Baidu") 



time.sleep(6) 



driver.quit() 



print("Time's up. Already quit.”) 

### 安装期间遇到的问题

若提示selenium不可识别，检测pycharm 设置中是否已导入对应版本的selenium 

Pycharm-preferences--project—project INterpreter 中selenium 版本号2.53.6 

<img src="http://bmob-cdn-24584.b0.upaiyun.com/2019/04/02/471cd71640cd059380987079d1bed61d.jpg" />

## 生成结果报告

需要安装HTMLTestRunner，对应python3版本 

<https://www.cnblogs.com/yrxns/p/9857812.html>

## 设置邮件提醒

