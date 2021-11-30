# Domain

[Domains](https://support.huaweicloud.com/intl/en-us/dns/) is a domain name management platform that provides domain name registration, transaction, monitoring, and protection services. 

Below steps is need for you to enable domains visit of your application:  

## Resolve Domain 

Resolve Domain mean that you set a mapping relations between domain and EI{}

1. Buy your Domain and register it
   ![Buy DNS](https://libs-websoft9-com.oss-cn-qingdao.aliyuncs.com/Websoft9/DocsPicture/en/huaweicloud/hwcloud-buydomain-websoft9.png)

2. Login to DNS console, lis all domains
   ![Add a record](https://libs.websoft9.com/Websoft9/DocsPicture/en/huaweicloud/huaweicloud-dns-websoft9.png)

3. Add an **Add Record** for it
   ![Add a record](https://libs.websoft9.com/Websoft9/DocsPicture/en/huaweicloud/huaweicloud-dnsrev-websoft9.png)

2. Save it and wait for 2-10 minute, then your DNS is take effect

## Bind Domain

The precondition for binding a domain is that HUAWEI CLOUD can accessed by domain name.

When there is only one website on the server, you can visit the website without binding domain. While considering the server security and subsequent maintenance, **Binding Domain** is necessary.

Steps for binding HUAWEI CLOUD domain are as follows:

1. Connect your Cloud Server;
2. Modify **vhost configuration file**,and change the **server_name** and **proxy_pass** if you want.
   ```text
   server
   {
   listen 80;
   server_name websoft9.yourdomain.com;  # Set your domain
       location / {
       proxy_pass  http://127.0.0.1:8880; # Set your port
   ...
   }
   ```
3. Restart Nginx service
   ```
   sudo systemctl restart nginx
   ```

## Domain Beian

If you ECS is created in China, and you want to use Domain for application, you must complete the **Domain Beian** for Government governance.

![Domain Beian](https://libs.websoft9.com/Websoft9/DocsPicture/en/huaweicloud/huaweicloud-dnsbeians-websoft9.png)

Refer to: [Domain Beian](https://beian.huaweicloud.com)