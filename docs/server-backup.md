# Backup

We know that no one (organization) can guarantee that the ECS will always be up and running. If the ECS fails to start or fails to connect, what would happen without backups? Is this worthwhile to try?

If there is a backup, it can be restored to the state at the time of backup, greatly reducing the loss.

The best backup method is automatic backup, you can use the Snapshot function of HUAWEI CLOUD to backup your Disk automatically.  

You can backup your disk by the below methods:  

## Automatic

You can use the HUAWEI CLOUD [**Cloud Backup and Recovery (CBR)**](https://support.huaweicloud.com/en-us/productdesc-cbr/cbr_01_0002.html) to backup your data.  

![Automatic backup](https://libs.websoft9.com/Websoft9/DocsPicture/en/huaweicloud/huaweicloud-cbr-websoft9.png)

### Cloud Disk Backups

Back up and restore cloud disks. You can use a cloud disk backup to restore data to a backup point or create a new disk.Backups of encrypted disks are automatically encrypted to ensure data security.

1. Login to Console, go to: 【Recovery Console】>【Cloud Disk Backups】

2. Then click the button 【Buy Disk Backup Vault】
   ![Buy Disk Backup Vault](https://libs.websoft9.com/Websoft9/DocsPicture/en/huaweicloud/huaweicloud-buydkbv-websoft9.png)

3. You can select disks will be applied to this Backup Vault
   ![Buy Disk Backup Vault](https://libs.websoft9.com/Websoft9/DocsPicture/en/huaweicloud/huaweicloud-buydkbv002-websoft9.png)

2. Suggest set the backup strategy 
   ![set the backup strategy](https://libs-websoft9-com.oss-cn-qingdao.aliyuncs.com/Websoft9/DocsPicture/en/huaweicloud/huaweicloud-buydkbv003-websoft9.png)
   
   ![set the backup strategy](https://libs-websoft9-com.oss-cn-qingdao.aliyuncs.com/Websoft9/DocsPicture/en/huaweicloud/huaweicloud-buydkbv004-websoft9.png)

### Cloud Server Backups

Back up and restore cloud servers, ensuring the security and consistency of your data.

1. Login to Console, go to: 【Cloud Server Console】>【Cloud Server Backups】

2. Then click the button 【Buy Disk Backup Vault】
   ![Buy Disk Backup Vault](https://libs.websoft9.com/Websoft9/DocsPicture/en/huaweicloud/huaweicloud-buydkbv-websoft9.png)

3. You can select Servers will be applied to this Backup Vault
   ![Buy Disk Backup Vault](https://libs.websoft9.com/Websoft9/DocsPicture/en/huaweicloud/huaweicloud-cbrbuyecsbks-websoft9.png)

4. Suggest set the backup strategy 

## Manual Backups

If you don't want to use automatic backups, you can manual backups by [Create Snapshot](/server-snapshot-image.md#create-snapshot) and [Create Image](server-snapshot-image.md#create-image)