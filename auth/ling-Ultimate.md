## 通过 Authlib-Injector 外置登录连接到服务器 （澪Ultimate）

*此方案仅支持 Android 移动设备且效果有待验证，推荐优先使用基岩版登录*

### 与服务器取得连接

1.  前往`澪Ultimate`作者的[爱发电](https://afdian.net/@boatmio)或[BiliBili空间](https://space.bilibili.com/35801833)下载

2.  安装并打开

3.  选择 登录-外置登录。请确保你拥有外置登录站的账号，如否，请[注册](https://user.turna.live/auth/register)

4.  填写外置登录验证服务器地址 `https://user.turna.live/api/yggdrasil`及你的账号密码

5.  将[authlib-injector](https://github.com/yushijinhun/authlib-injector/releases)下载至你设备根目录下的`MioLauncher`文件夹

6.  填写启动参数 `-javaagent:/path/to/your/authlib-injector=https://user.turna.live/api/yggdrasil`


    !>如你依照以上步骤操作，此处的`/path/to/your/authlib-injector`在大部分安卓设备上应为`/storage/emulated/0/MioLauncher/authlib-injector-x.x.x.jar`
    
    
7.  启动并加入服务器

8.  [开始玩耍](/game/Opening)吧!


### 推荐安装 Mod

1. Sodium

在跟随以上步骤安装完成后，进入世界大概率会遇到极端的卡顿现象，推荐安装 Sodium 来缓解

2. LambdaControls

为触摸操作提供更好的支持
