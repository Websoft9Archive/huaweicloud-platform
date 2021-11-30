# 账号密码

下面分别就数据库和操作系统的账号密码进行说明：

## 数据库

### 用户名、密码和管理地址

不同的数据库有一定的差异，参考下表：

| 名称                    | 用户名     | 密码           | 可视化管理地址           |
| ----------------------- | ---------- | -------------- | ------------------------ |
| MySQL/Mariadb PHP环境中 | root       | 服务器中获取 | http://公网IP/phpmyadmin |
| MySQL/Mariadb 其他      | root       | 服务器中获取  | http://公网IP:9090       |
| PostgreSQL              | postgres   | 服务器中获取  | http://公网IP:9090       |
| Mongodb                 | adminmongo | 服务器中获取  | http://公网IP:9091       |
| Oracle                  | system     | 服务器中获取 | 暂无                     |
| SQLServer               | sa         | 自动设置 | 使用客户端管理           |

### 获取数据库密码

#### Linux系统

对于Linux系统来说，数据库密码存储在您的服务器指定文件中：*`/credentials/password.txt`*。建议通过云控制台直接连接服务器，进入命令终端，运行cat命令获取数据库密码：

![运行cat命令](https://libs.websoft9.com/Websoft9/DocsPicture/zh/common/catdbpassword-websoft9.png)

#### Windows系统

对于Windows系统来说，数据库密码存储在您的服务器指定文件中：*`c:/credentials/password.txt`*

服务器的桌面上会有打开数据库密码文件的快捷方式


## 操作系统

华为云 Linux 系统默认的账号名称为：`root`  
华为云 Windows 系统默认的账号名称为：`administrator`