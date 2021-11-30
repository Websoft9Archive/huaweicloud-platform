# 部署产品

Websoft9 已经在 华为云云市场 上提供了多款产品（**镜像是云上的一种软件产品交付形态**），覆盖常用的云场景，收到用户的良好反馈。

>  是不是想了解有哪些优质的镜像呢？点击 [此处](https://marketplace.huaweicloud.com/seller/e57458aa054b430fb2f82a066105f986) 查看 Websoft9 在华为云上发布的所有镜像。

那么如何在华为云上使用这些镜像呢？有两种方法：

## 云市场部署

1. 访问 [华为云云市场](https://marketplace.huaweicloud.com/all/?q=JXdlYnNvZnQ5JQ) 网站 或 [Websoft9店铺地址](https://marketplace.huaweicloud.com/seller/e57458aa054b430fb2f82a066105f986)

2. 搜索关键字"websoft9"，网站会列出所有相关的镜像
   ![搜索Websoft9镜像](https://libs.websoft9.com/Websoft9/DocsPicture/zh/huaweicloud/huaweicloud-buy-websoft9.png) 

3. 点击您所需的产品，进入产品详情页后点击"立即购买"按钮 或点击“自定义云主机”
   ![立即购买](https://libs.websoft9.com/Websoft9/DocsPicture/zh/huaweicloud/huaweicloud-buyimage-websoft9.png) 
4. 接下来系统会自动要求购买一台新服务器：选择计费模式、规格、网络和安全组等设置
5. 等待几分钟，ECS创建完成后，镜像会作为ECS实例的系统盘启动，即镜像自动部署到实例中


## 购买服务器部署

购买ECS或控制台创建实例过程中，可以选择Websoft9的镜像作为系统启动盘

1. 登录到华为云管理控制台->弹性云服务器ECS，点击“购买弹性云服务器”，
   ![进入ecs控制台购买服务器](https://libs.websoft9.com/Websoft9/DocsPicture/zh/huaweicloud/huaweicloud-buyecs-websoft9.png)
2. 在镜像一栏，选择镜像市场->从镜像市场获取更多选择（含操作系统）。
3. 然后搜索关键件词“**网久**”，列出相关镜像
   ![选择Websoft9镜像](https://libs.websoft9.com/Websoft9/DocsPicture/zh/huaweicloud/huaweicloud-selectimage-websoft9.png)

4. 选择一个你所需的镜像，开始创建ECS实例
5. 后续动作基本都会要求用户完成：选择计费模式、规格、网络和安全组等设置
6. 等待几分钟，ECS创建完成后，镜像会作为ECS实例的系统盘启动，即镜像自动部署到实例中

## 切换操作系统部署

镜像除了可以在创建新服务器之时购买，针对已有服务器，也可以通过**切换操作系统**的方式使用镜像。

> 需要注意的是，重装系统意味着系统数据全部会格式化，所以请注意做好数据的备份。

1. 登录到华为云管理控制台，在”实例“中先停止服务器，依次选择：更多->切换操作系统 
   ![切换操作系统](https://libs.websoft9.com/Websoft9/DocsPicture/zh/huaweicloud/huaweicloud-changesysdisk-websoft9.png)

2. 确认更换后，镜像类型选择“镜像市场”，然后输入搜索关键字“**网久**”，根据提示设置新密码
   ![选择Websoft9镜像](https://libs.websoft9.com/Websoft9/DocsPicture/zh/huaweicloud/huaweicloud-changeimage-websoft9.png)

3. 请耐心等待几分钟，直至更换完成

除了镜像订阅部署之外，你还可以通过我们发布到 [Github](https://github.com/websoft9)上的 Ansible 脚本，来实现自动部署。