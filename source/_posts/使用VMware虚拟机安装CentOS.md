---
title: 使用VMware虚拟机安装CentOS
abbrlink: cc055d6d
date: 2024-03-27 11:28:48
tags:
---
# 使用VMware Workstation PRO17在Windows上安装CentOS9图形界面版详细步骤
#### 本文所用系统安装地址：https://mirrors.tuna.tsinghua.edu.cn/centos-stream/9-stream/BaseOS/x86_64/iso/CentOS-Stream-9-latest-x86_64-dvd1.iso

### 打开软件进入主页，选择创建虚拟机
![1](https://pic.imgdb.cn/item/661f16d50ea9cb14035a560c.png)
### 选择典型
![2](https://pic.imgdb.cn/item/661f16d50ea9cb14035a5696.png)
### 选择稍后安装系统，便于后续对虚拟机的自定义
![3](https://pic.imgdb.cn/item/661f16d50ea9cb14035a56f9.png)
### 客户机操作系统选择Linux
![4](https://pic.imgdb.cn/item/661f16d50ea9cb14035a5772.png)
### 为虚拟机重命名，选择虚拟机位置（虚拟机将在此处被分配硬盘空间）
![5](https://pic.imgdb.cn/item/661f16d50ea9cb14035a57e2.png)
### 设置虚拟机硬盘大小使用推荐设置即可，
![6](https://pic.imgdb.cn/item/661f16df0ea9cb14035a7c5a.png)
### 初始设置完毕，点击完成
![7](https://pic.imgdb.cn/item/661f16df0ea9cb14035a7cc6.png)
### 在右边找到刚才创建的虚拟机，打开页面，点击编辑虚拟机设置
![8](https://pic.imgdb.cn/item/661f16df0ea9cb14035a7cfa.png)
### 在此处可以进行虚拟机的硬件资源分配，建议处理器和内存最大不要超过物理机的50%
![9](https://pic.imgdb.cn/item/661f16e00ea9cb14035a7d43.png)
### 点击选择CD/DVD
![10](https://pic.imgdb.cn/item/661f16e00ea9cb14035a7d8e.png)
### 在右边连接一栏选择使用ISO映像文件，点击浏览，选择提前准备好的系统镜像，选择完毕后保存设置，关闭虚拟机设置窗口，点击开启此虚拟机，等待虚拟机启动。
![11](https://pic.imgdb.cn/item/661f16e60ea9cb14035a9058.png)
#### 安装其他操作系统则换成对应iOS映像即可，安装过程大同小异
### 虚拟机启动后，会自动运行刚才配置好的系统文件，等待跳出第一个选择界面，选择第一个选项“install CentOS Stream 9”
![12](https://pic.imgdb.cn/item/661f16e60ea9cb14035a90e3.png)
### 系统会自动进行安装前的准备，根据电脑硬件不同，此过程可能较慢，无需进行任何操作，等待加载完成
![13](https://pic.imgdb.cn/item/661f16e60ea9cb14035a9124.png)
### 加载完成后可以看到一个图形界面，根据安装向导操作即可
![14](https://pic.imgdb.cn/item/661f16e60ea9cb14035a919c.png)
### 红字标出的设置项强制用户进行手动设置（设置管理员密码时若想设置简单密码，只需要设置后多次点击完成即可）
![15](https://pic.imgdb.cn/item/661f16e60ea9cb14035a92c3.png)
### 将红字标出的项目都设置完成后，即可点击左下角按钮进行系统安装（安装时可能会进行下载，提前保持网络通畅）
![16](https://pic.imgdb.cn/item/661f16ee0ea9cb14035aa702.png)
### 等待安装完毕
![17](https://pic.imgdb.cn/item/661f16ee0ea9cb14035aa77b.png)
![18](https://pic.imgdb.cn/item/661f16ee0ea9cb14035aa7b5.png)

![19](https://pic.imgdb.cn/item/661f16ee0ea9cb14035aa815.png)
### 顺利进入系统，至此，系统安装完成
