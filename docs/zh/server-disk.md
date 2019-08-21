# 云硬盘

对于华为云平台来说，云硬盘（磁盘）可以是单独的一种计算资源（单独创建、单独计费、单独管理等），同时也可以被集成到服务器实例，作为其中的一个组件。

## 增加硬盘

1. 登录到云服务器控制台，点击**云硬盘**下的**磁盘**
2. 点击“购买磁盘”按钮
   ![购买磁盘](https://libs.websoft9.com/Websoft9/DocsPicture/zh/huaweicloud/huaweicloud-createdisk-websoft9.png)
3. 设置磁盘类型，大小等，确认无误后开始创建
4. 将创建好的磁盘，挂载到ECS实例
   ![挂载磁盘](https://libs.websoft9.com/Websoft9/DocsPicture/zh/huaweicloud/huaweicloud-attachdisk-websoft9.png)
5. “磁盘挂载”执行成功后，需登录本实例对挂载的磁盘进行“初始化数据盘”的操作：
    - Windows, 请参考华为云官方文档 [Windows初始化数据盘](https://support.huaweicloud.com/qs-ecs/zh-cn_topic_0030831989.html)
    - Linux，请参考华为云官方文档 [Linux初始化数据盘](https://support.huaweicloud.com/qs-ecs/zh-cn_topic_0030831989.html) 
5. 以上所有设置后方可使用磁盘

## 卸载硬盘

将磁盘从ECS中解除绑定关系(卸载)，操作如下

1. 登录到云服务器控制台，点击**云硬盘**下的**磁盘**
2. 找到所需卸载的磁盘，依次打开：更多->卸载
   ![卸载磁盘](https://libs.websoft9.com/Websoft9/DocsPicture/zh/huaweicloud/huaweicloud-ditachdisk-websoft9.png)
3. 根据提示完成后续操作

> 磁盘卸载后，会保留，不会被删除，可以被其他服务器挂载

## 扩容

华为云支持在线扩容**系统盘**和**数据盘**，即无需重启ECS实例便可以完成扩容。

1. 登录到服务器控制台，点击**云硬盘**下的**磁盘**
2. 找到所需卸载的磁盘，点击“扩容”
   ![修改卷](https://libs.websoft9.com/Websoft9/DocsPicture/zh/huaweicloud/huaweicloud-changedisks-websoft9.png)
3. 根据提示完成后续操作

> 磁盘只支持扩容，不支持减容。