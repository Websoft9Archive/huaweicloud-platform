# 创建

下面介绍华为云上创建服务器实例的说明。

创建实例最基本的条件是需要给服务器准备一个系统盘的启动模板文件，这个模板最常见的表现形式就是镜像文件

下面介绍基于镜像创建云服务器的操作步骤：

## 创建弹性云服务器

1. 登录到华为云管理控制台->弹性云服务器ECS，点击“购买弹性云服务器”，
   ![进入ecs控制台购买服务器](https://libs.websoft9.com/Websoft9/DocsPicture/en/huaweicloud/huaweicloud-buyecs-websoft9.png)
2. 选择计费模式、区域、规格等
   ![选择ECS规格](https://libs.websoft9.com/Websoft9/DocsPicture/en/huaweicloud/huaweicloud-guige-websoft9.png)

   - 包年/包月：一口价包干付费制
   - 按需付费：按小时付费，用一小时给一小时的钱

3. 在镜像一栏，有多种选择。
   - 公共镜像：华为云官方提供的操作系统镜像
   - 私有镜像：用户自己的镜像
   - 共享镜像：其他人共享给用户的镜像
   - 市场镜像：提供预装操作系统、应用环境和各类软件的优质第三方镜像。无需配置，可一键部署，满足建站、应用开发、可视化管理等个性化需求。

4. 如果选择镜像市场，可以通过搜索关键件词“网久”，列出我们相关镜像
   ![选择Websoft9镜像](https://libs.websoft9.com/Websoft9/DocsPicture/en/huaweicloud/huaweicloud-selectimage-websoft9.png)

4. 选择一个你所需的镜像，开始创建弹性云服务器
5. 后续动作基本都会要求用户完成：网络和安全组、密码、公网带宽等设置，带宽建议按流量计费
![选择带宽](https://libs.websoft9.com/Websoft9/DocsPicture/en/huaweicloud/huawei-netwithpayasgo-websoft9.png)
6. 等待几分钟，弹性云服务器创建完成后，镜像会作为服务器的系统盘启动，即镜像自动部署到实例中

## 秘钥对

在创建弹性云服务器时，如下采用秘钥对作为登录凭证，需要提前创建秘钥对

1. 登录华为云控制台，打开：弹性云服务器->秘钥对，点击“**创建秘钥对**”按钮
   ![创建秘钥对](https://libs.websoft9.com/Websoft9/DocsPicture/en/huaweicloud/huaweicloud-createkeys-websoft9.png)
2. 为秘钥对命名，例如“myKey”
3. 点击确认后系统会自动将秘钥对文件 myKey.pem 保存到本地电脑
4. 私钥只能下载一次，请妥善保管