# dzzoffice

### 官方网站:http://dzzoffice.com

### DzzOffice 特点：
* 支持触屏操作，良好支持平板设备访问。
* 继承了windows的使用习惯，操作简单，易上手。
* 云存储、私有云的可视化管理
* 可视化安装向导、安装部署简单
* 大文件上传、批量上传、文件夹上传、拖拽上传
* 多种应用接入方式，强大的扩展性
* 灵活多变的个性化设置


### DzzOffice1.3更新说明

1. 语言包和程序分离，支持扩展多语言版本。

2：可以添加服务器本地磁盘作为存储位置。

3：修复阿里云连接时的一些问题。

4：七牛云增加区域选择。

5：优化支持php7。

6：修改文件管理，支持按部门查看文件。

7: 支持修改用户所属用户组。

8：jQuery升级到3.0；

9：模板解析优化，支持模板合并，多语言解析。

10：全新的图片浏览器。

11：修改机构和用户管理，不再显示没有权限管理的机构。

12：系统缩略图修改，支持small middle large三种尺寸，并且可以设置各尺寸的具体数值。

13：支持多选下载

14：其他一些修复和优化。 



### 升级方法和步骤

1.  进入您原来的系统，关闭您的站点。进行数据备份

2. 备份数据库和备份文件（如果有程序文件或风格文件的改动）,

3. 下载并解压缩最新版的程序包

4. 程序包解压缩后，可以看到 upload, update 两个目录

5. 上传upload目录中的程序到服务器dzzoffice根目录，如果提示需要覆盖，则选择“是”

6. 将压缩包中 update 目录中的 update.php  程序上传到 install 目录。并删除 install 目录中的 index.php

6. 访问 http://您的域名/install/update.php。

7. 按照程序提示，直至所有升级完毕。删除install/update.php 程序，以免被恶意利用。

8. 进入管理员桌面，更新缓存，并对新功能进行设置和测试。

### 安装方法和步骤

1. 上传 upload 目录中的文件到服务器

2. 设置目录属性（windows 服务器可忽略这一步）
	以下这些目录需要可读写权限
	./core/config
	./data 含子目录

3. 执行安装脚本 /install/
   请在浏览器中运行 install 程序，即访问 http://您的域名/install/

4. 参照页面提示，进行安装，直至安装完毕

5.进入桌面，在开始面板中打开“系统工具”应用，更新系统缓存。

### 您在安装或升级过程中遇到任何问题，可通过以下途径解决

1. 到我们的[讨论区](http://dev.dzzoffice.com)寻求帮助和支持。

2. 商业用户可以根据您购买的服务，使用电话、MSN、QQ、论坛等多种方式寻求技术支持
