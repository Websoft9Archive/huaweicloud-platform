# Create

Here's how to create a ECS on HUAWEI CLOUD.

## ECS Creation

1. Login to Console, open:【Cloud Server Console】>【Elastic Cloud Server】>【Buy ECS】
   ![create ecs](https://libs.websoft9.com/Websoft9/DocsPicture/en/huaweicloud/huaweicloud-buyecs-websoft9.png)

2. Select the billing mode, instance type like these
   ![type](https://libs.websoft9.com/Websoft9/DocsPicture/en/huaweicloud/huaweicloud-guige-websoft9.png)

   - Subscription: Allows you to pay upfront and then use the service over a period of time.  
   - Pay-As-You-Go: A billing method based on the amount of resources you actually use.  
   - Preemptible Instance: A billing method based on the amount of resources you actually use. 

3. Select the **Image** step is very important

   - Public Image: Alibaba Cloud provides official public images. 
   - Custom Image: Created from system snapshots of yourself
   - Shared Image: Other user shared for you
   - Marketplace Image: Alibaba Cloud Marketplace provides hundreds of high-quality third-party images that have undergone a strict review process.

4. If you use the Marketplace Image, suggest use the search key "websoft9"

   ![search websoft9 image](https://libs.websoft9.com/Websoft9/DocsPicture/en/huaweicloud/huaweicloud-selectimage-websoft9.png)

4. Select the image you want to use

5. Go to next steps, include set Networking, System Configurations and so on

6. Wait 2-3 minutes for the ECS running when completed these steps

## Key Pairs

You should create **Key Pairs** before create ECS if you want to use Key Pairs for ECS connection

1. Login to Console, open:【Cloud Server Console】>【Key Pairs】
   ![Key Pairs](https://libs.websoft9.com/Websoft9/DocsPicture/en/huaweicloud/huaweicloud-createkeys-websoft9.png)

2. Set the **SSH Key Pair Name** and select **Creation Mode**

3. When you complete the creation, please download the ××××.pem to your local computer