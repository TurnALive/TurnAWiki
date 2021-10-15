## 通过 澪Ultimate 进行连接至服务器

*此方案仅支持 Android 移动设备且效果有待验证，推荐优先使用基岩版登录*

*作者的 [爱发电] (https://afdian.net/@boatmio) 

### 与服务器取得连接

1.  前往 [此处](https://www.lanzoui.com/iocKGupqa6h?w) 下载 澪Ultimate

*在安装前请确保储存空间够用，本wiki所附上的下载链接为作者官方介绍视频所提供，后续版本可能更新，请以官方为准*

2.  安装 澪Ultimate，并打开

3.  如有初始化，请等待初始化完成后登录

4.  登录

*登录分为正版登录和外置登录，正版登录与hmcl基本一致，所以这里不再赘述*

4.1  先在登录界面点击登录，外置登录，输入您的邮箱或外置登录的游戏名称以及密码。

4.2  在下方输入外置登录的地址 'https://user.turna.live/api/yggdrasil' ，并登录

4.3  登录后勾选你刚刚登录的账户

4.4  打开您设备的文件管理器

4.5  在您设备的根目录有一文件夹叫 MioLauncher，下载 'authlib-injector-1.1.38.jar' [链接,密码:ak1r] (https://xzzdr.lanzoui.com/iPqbtvdnpjg) 放进此文件夹

4.6  打开 澪Ultimate ，将启动参数修改为 -Xmx1024M -javaagent:/storage/emulated/0/MioLauncher/authlib-injector-1.1.38.jar=https://user.turna.live/api/yggdrasil

4.7  下载相对应的游戏版本后，启动游戏

5. 加入服务器的步骤与标准的 Minecraft Java Edition 相差不大，在此略过

### 推荐安装 Mod

1. Sodium

在跟随以上步骤安装完成后，进入世界大概率会遇到极端的卡顿现象，推荐安装 Sodium 来缓解

2. LambdaControls

为触摸操作提供更好的支持