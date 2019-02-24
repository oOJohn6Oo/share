## WireGuard —— Windows/Android 客户端简单使用教程(转自[逗比根据地](doub.life))

- Android[官方版]()[TunSafe版]()

1. ## 安装
可以从google play或者APKPure搜索`wireguard`直接安装或者点击上面的链接下载安装。
2. ## 使用
打开客户端后，一片空白，我们点击右下角的 [+加号蓝色] 按钮，可以看出弹出几个添加配置的选项，分别是：

选择客户端配置文件
扫描二维码
创建文件
推荐前两种。

第一种就是将客户端配置文件传到手机上，然后选择配置文件就行了（配置文件名不要包含中文）。

第二种即你去找个生成二维码图片的网站，复制你的客户端配置文件内容去这些网站将其生成为二维码，然后手机扫描二维码即可添加成功，添加时会提示你要给该配置文件起个名字。

### 配置不走vnp的应用
我们点击配置名称看到配置详情后，点击右上角的 [铅笔] 按钮，即可修改配置信息，其中有个 [0 EXCLUDED APPLICATIONS] 选项，点击后就可以 勾选 不走vnp的应用。
- [Windows](https://tunsafe.com/downloads/TunSafe-1.4.exe)
1. ## 安装
下载后，右键 [以管理员方式运行] 安装程序：
出现使用条款，直接点击 [I Agree] 按钮继续。
下面是选择要安装的程序，客户端自身 和 TAP虚拟网卡程序，默认全部勾选，点击 [Next >] 按钮继续。
选择安装目录后，点击 [Install] 按钮开始安装。
然后等待安装完成，安装过程中可能会因为涉及到安装虚拟网卡，系统会提示你要安装设备软件，记得勾选左下角的 [信任xxx....] ，然后点击 [安装] 按钮。
2. ## 使用
我们点击 File - Import File 选项，就会提示你选择客户端配置文件(如下多个图演示)。

当然你也可以点击 File - Browse in Explorer 选项，会直接打开该vnp客户端的客户端配置文件存放目录，你将你的客户端配置文件(xx.conf)复制过去就行了。

添加完后，我们选择 client 这个我们刚刚添加的vnp客户端配置，然后点击右侧的 [Connect] 按钮。[Disconnect] 按钮代表停止链接。

该软件的托盘菜单中也有 [Connect]、[Reconnect]、[Disconnect] 选项。

点击右侧的 [Edit Config] 按钮即可编辑当前配置文件。

另外，软件 Options - Service Mode 中的选项分别对应的是：

Don’t Use a Service - 不使用服务
Foreground Mode (Close connection when closing TunSafe) - 前台模式（关闭TunSafe时关闭连接）
Background Mode (Stay connected when closing TunSafe) - 后台模式（关闭TunSafe时保持连接状态）
Resume Connection when Windows Starts - Windows启动时自动连接
Minimize to Tray when Windows Starts - Windows启动时最小化到托盘

- [MacOS](https://itunes.apple.com/us/app/wireguard/id1451685025?ls=1&mt=12)
- [iOS](https://itunes.apple.com/us/app/wireguard/id1441195209?ls=1&mt=8)

