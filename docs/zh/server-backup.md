# 备份

我们知道任何人（组织）都无法保证**云服务器**永远正常运行状态。假如云服务器出现无法启动或无法连接的故障，若没有备份会是什么样的后果？这样的教训是否值得尝试？

如果有备份，就能够恢复到备份之时的状态，大大降低损失。

华为云上有自动备份和手动备份两种云端备份方案

## 自动备份

自动备份就是使用华为云 [**云备份服务**](https://www.huaweicloud.com/product/cbr.html)（Cloud Backup and Recovery，以下简称"CBR"）

![云备份](https://libs.websoft9.com/Websoft9/DocsPicture/zh/huaweicloud/huaweicloud-cbr-websoft9.png)

华为云备份的基本原理是基于快照技术的数据保护，华为云备份针对业务场景，包含云服务器备份、云硬盘备份、应用备份、存储备份、VMware备份功能。

下面介绍云硬盘备份和云服务器备份两种方案：

### 云硬盘备份

云硬盘备份提供对云硬盘的基于快照技术的数据保护。

1. 登录到华为云备份服务控制台
2. 购买云硬盘备份存储库
   > 存储库是存放服务器和磁盘产生的备份副本的容器，您可以将服务器和磁盘绑定至存储库并绑定备份策略，为您的数据提供保障。

   ![云硬盘备份存储库](https://libs.websoft9.com/Websoft9/DocsPicture/zh/huaweicloud/huaweicloud-cbrbuydisks-websoft9.png)

3. 购买过程中可以立即选择所需备份的硬盘、设置备份策略，也可以跳过以后再设置
   ![云硬盘备份存储库](https://libs.websoft9.com/Websoft9/DocsPicture/zh/huaweicloud/huaweicloud-cbrbuydiskss-websoft9.png)

2. 备份策略设置
   ![云硬盘备份策略](https://libs.websoft9.com/Websoft9/DocsPicture/zh/huaweicloud/huaweicloud-cbrdiskpl-websoft9.png)

### 云服务器备份

云服务器备份提供对弹性云服务器和裸金属服务器的基于多云硬盘一致性快照技术的数据保护。

1. 登录到华为云备份服务控制台

2. 购买云服务器备份存储库
   ![云服务器备份存储库](https://libs.websoft9.com/Websoft9/DocsPicture/zh/huaweicloud/huaweicloud-cbrbuyecsbk-websoft9.png)

3. 购买过程中可以立即选择所需备份的服务器、设置备份策略，也可以跳过以后再设置
   ![云服务器备份存储库](https://libs.websoft9.com/Websoft9/DocsPicture/zh/huaweicloud/huaweicloud-cbrbuyecsbks-websoft9.png)

2. 备份策略设置
    ![云服务器备份策略](https://libs.websoft9.com/Websoft9/DocsPicture/zh/huaweicloud/huaweicloud-cbrecspl-websoft9.png)

## 手工备份

如果不做自动备份，而是手动根据需要备份，华为云也支持常见的备份方式：自定义快照和自定义镜像

### 创建快照

华为云可以基于磁盘直接创建快照

1. 登录到华为云服务器控制台
2. 在云硬盘列出所有磁盘，对需要操作的磁盘进行“创建快照”操作
    ![创建快照](https://libs.websoft9.com/Websoft9/DocsPicture/zh/huaweicloud/huaweicloud-dkcreatesnapshot-websoft9.png)
3. 根据提示完成后续操作

### 创建镜像

1. 登录到华为云控制台->弹性云服务器，找到需要操作的目标服务器
2. 依次打开：更多->创建镜像
   ![创建自定义镜像](https://libs.websoft9.com/Websoft9/DocsPicture/zh/huaweicloud/huaweicloud-createimage-websoft9.png)
3. 根据提示完成后续操作