# Snapshot and Image

The reason we put snapshots and image together is because there is a certain relationship between the two, and even there is an alternate relationship.

## Relationship

A snapshot is a "photographing" of a disk. As the name suggests, it is to back up the data of a disk at a certain point in time. It is a backup method.  

Following key information points are listed:

* A snapshot can be created based on the disk.
* A image can be created by snapshot, and the image cannot be directly converted into a snapshot.
* You can create a ECS directly based on Image, and you can create a image directly based on the ECS.

## Create Snapshot

You can create snapshot for disk to backup

1. Login to Console, go to: 【Cloud Server Console】>【Elastic Volume Service	】>【Disk】

2. Select one Disk which you want to create snapshot for it
   ![Create snapshot](https://libs.websoft9.com/Websoft9/DocsPicture/en/huaweicloud/huaweicloud-dkcreatesnapshot-websoft9.png)

3. Complete the next steps

## Create Image

1. Login to Console, list all ECS from 【Cloud Server Console】

2. Open the menu: 【More】>【Manage Image/Disk】>【Create Image】
   ![Create Image](https://libs.websoft9.com/Websoft9/DocsPicture/en/huaweicloud/huaweicloud-createimage-websoft9.png)
   
3. Complete the next steps