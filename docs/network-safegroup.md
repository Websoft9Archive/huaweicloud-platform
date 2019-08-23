# 安全组

安全组是管理云服务器端口的功能，端口是服务器上应用程序与外部访问出入访问的通道。下面以**开启80端口为例**，为您介绍安全组的使用

1. 登录到华为云控制台->云服务器

2. 华为云控制台-云服务器-点击主机ID链接，打开服务器详细信息页面

3. 依次点击：安全组->更改安全组->管理安全组
   ![ec2更改安全组](https://libs.websoft9.com/Websoft9/DocsPicture/en/huaweicloud/huaweicloud-safegroup001-websoft9.png)
   
   ![ec2更改安全组](https://libs.websoft9.com/Websoft9/DocsPicture/en/huaweicloud/huaweicloud-safegroup002-websoft9.png)
   
4. 进入管理安全组页面->快速添加规则
   ![ec2更改安全组入](https://libs.websoft9.com/Websoft9/DocsPicture/en/huaweicloud/hwcloud-safe80-websoft9.png)

5. 选择 HTTP(80) 端口，点击确认完成设置

> 以上设置方法是最为简单的一种，更多请参考[华为云官方安全组教程](https://support.huaweicloud.com/usermanual-ecs/zh-cn_topic_0030878383.html)进行更为安全、精准的设置。