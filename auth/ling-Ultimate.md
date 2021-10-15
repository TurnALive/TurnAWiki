## 通过 澪Ultimate 进行连接至服务器

*此方案仅支持 Android 移动设备且效果有待验证，推荐优先使用基岩版登录*

*作者的 [爱发电] (https://afdian.net/@boatmio) 

### 与服务器取得连接

1.  前往 [此处](https://afdian.net/@boatmio) 或 [此处](https://space.bilibili.com/35801833)下载 澪Ultimate

*在安装前请确保储存空间足够*

2.  安装 澪Ultimate，并打开

3.  如有初始化，请等待初始化完成后登录

4.  登录

*登录分为正版登录和外置登录，正版登录与hmcl基本一致，所以这里不再赘述*

4.1  先在登录界面点击登录，外置登录，输入您的邮箱或外置登录的游戏名称以及密码。

4.2  在下方输入外置登录的地址 'https://user.turna.live/api/yggdrasil' ，并登录

4.3  登录后勾选你刚刚登录的账户

4.4  打开您设备的文件管理器

4.5  在您设备的根目录有一文件夹叫 MioLauncher，下载 'authlib-injector-x.x.xx.jar' [链接] (https://github.com/yushijinhun/authlib-injector/releases) 放进此文件夹

4.6  打开 澪Ultimate ，将启动参数修改为 -XmxAAAM -javaagent:/storage/emulated/0/MioLauncher/authlib-injector-x.x.x.jar=https://user.turna.live/api/yggdrasil
*注：此处的AAA可自由设置，authlib-injector所下载的版本号不定，请以下载版本为主*

5. 选择安装与当前服务器世界对应的版本并启动

6. 加入服务器的步骤与标准的 Minecraft Java Edition 相差不大，在此略过

### 推荐安装 Mod

1. Sodium

在跟随以上步骤安装完成后，进入世界大概率会遇到极端的卡顿现象，推荐安装 Sodium 来缓解

2. LambdaControls

为触摸操作提供更好的支持
