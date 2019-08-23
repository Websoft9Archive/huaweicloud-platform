# 公网IP地址

## 查看

1. 登录到华为云控制台->ECS
2. 打开要查看公网IP的实例，我们会看到 **IP地址（公）** 
   ![查看公网IP](https://libs.websoft9.com/Websoft9/DocsPicture/zh/huaweicloud/huaweicloud-getpublicip-websoft9.png)
3. 如果实例没有公网IP地址项（或为空），需挂载一个弹性公网IP（[参考文档](https://help.aliyun.com/document_detail/72125.html)）

## 绑定

如果云服务器没有弹性IP，具体操作步骤如下：

1. 登录云服务器管理控制台。
2. 点击服务器名称，进入服务器详情页面。
3. 找到“弹性公网IP”标签，找到“绑定弹性公网IP”按钮
   ![img](https://libs.websoft9.com/Websoft9/DocsPicture/zh/huaweicloud/huaweicloud-bindeip-websoft9.png)
4. 根据提示完成后续操作

> 如果没有可用的弹性公网IP，需要实现购买弹性公网IP