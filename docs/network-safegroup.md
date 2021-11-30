# Security Group

A [Security Group](https://support.huaweicloud.com/en-us/usermanual-ecs/en-us_topic_0140323157.html) acts as a virtual firewall for Elastic Compute Service (ECS) instances to control inbound and outbound traffic and improve security. You can use security groups and security group rules to define security domains in the cloud.  

Below is a sample for you how to **Enable TCP:80** port on security group:  

1. Login to console, lis all ECS by 【Cloud Server Console】>【Security Group】

2. Add a rule or modify a rule

   ![ecs Security Group](https://libs.websoft9.com/Websoft9/DocsPicture/en/huaweicloud/huaweicloud-safegroup001-websoft9.png)
   ![ecs Security Group](https://libs.websoft9.com/Websoft9/DocsPicture/en/huaweicloud/huaweicloud-safegroup002-websoft9.png)

4. Then, add a new rule by click the 【Add Rule】button授权对象一般为较为合适
   ![ecs Security Group](https://libs.websoft9.com/Websoft9/DocsPicture/en/huaweicloud/hwcloud-safe80-websoft9.png)

   - Destination set to **HTTP(80)**
   - Source set to **0.0.0.0/0**

5. Save it 