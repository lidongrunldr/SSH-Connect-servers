# 📘: SSH-Connect-servers 📘:
如何通过SSH远程连接服务器
### **1 从vscode上下载Remote-SSH插件**

<p align="center">
  <img src="图像.jpg" width = "400" height = "300" alt="按钮" />
</p>
### **2 配置服务器文件**

点击vscode左下角的按钮
<p align="center">
  <img src="截屏2024-12-11 19.33.28.png" width = "400" height = "300" alt="按钮" />
</p>

### **3 点击后顶部下拉菜单中点击连接到主机**

<p align="center">
  <img src="图像2024-12-11 19.34.jpg" width = "400" height = "300" alt="下拉菜单"/>
</p>

### **4 配置config文件**

config文件的默认路径为`/users/ldr/.ssh/config`

<p align="center">
  <img src="截屏2024-12-11 19.47.58.png" width = "400" height = "300" alt="config" />
</p>
Host名可以自己取

# 服务器文件管理软件
* windows端可以选择WinSCP，稳定且操作简单
* mac端可以选择用FileZilla，需要下载软件后点击左上角图标，在我的站台下面新建站台，然后将协议改成SFTP（默认是FTP，这个协议太古老了，会连接不上服务器），然后输入主机地址，端口（连接埠），密码，用户名。登入形式选择一般，点连线即可，速度很快。
