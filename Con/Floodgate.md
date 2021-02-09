## 通过 Minecraft Bedrock Edition 连接到服务器

    1. 与服务器取得连接
    2. 绑定 Minecraft Java Edition 帐号
    3. 基岩版可能会需要用到的指令

### 与服务器取得连接

1. 下载1.16.x基岩版Minecraft（全平台）

![index.jpg](https://ddns.xsling.xyz:3561/images/2021/01/01/index.jpg)

2. 在服务器页面找到添加服务器，并填写相关信息

服务器名称:`TurnALive`
服务器地址:`se.turna.live`
端口:`19132`

![addserver.jpg](https://ddns.xsling.xyz:3561/images/2021/01/01/addserver.jpg)

3. 保存后点击新增项后即可连接到服务器

![checkin.jpg](https://ddns.xsling.xyz:3561/images/2021/01/01/checkin.jpg)

![turna.jpg](https://ddns.xsling.xyz:3561/images/2021/01/01/turna.jpg)


![jeview.jpg](https://ddns.xsling.xyz:3561/images/2021/01/01/jeview.jpg)

*JE玩家视角*

### 绑定 Minecraft Java Edition 帐号

1. 请分别登录 Java 与基岩版帐号并连接到服务器

1. 其中一端执行 <kbd>/linkaccount</kbd> 以获取绑定验证码

3. 另一端执行 <kbd>/linkaccount \<收到的绑定验证码></kbd>

4. 完成了！您的基岩版客户端将被请出服务器，请将两版本客户端都退出，再次登录基岩版即可以对应 Java 版帐号的身份游玩了

### 您可能需要在基岩版中使用这些指令来代替 Java 版的对应功能

1.  <kbd>/geyser offhand</kbd> 切换副手

    - 请注意基岩版无论何时副手的物品都不能被直接使用。您可以按住潜行使用盾牌、可以将副手的箭作为发射物装填、可以触发不死图腾，特殊装备的效果也可以生效，但不能使用副手的物品或放置副手的方块，要使用它们必须切换到主手

1. <kbd>/geyser statistics</kbd> 查看统计信息

    - 受 Geyser 限制统计信息中所有数据均为最小单位，距离单位为厘米，时间单位为秒

1. <kbd>/geyser advancements</kbd> 查看成就信息

    - 拥有特殊的用户界面，无其他与 Java 版差异

1. <kbd>/glist</kbd> 显示正确的在线玩家

    - 由于服务器应用插件生成了虚拟玩家用于 Tab 在线玩家页面的排版，基岩版在暂停界面直接查看在线玩家会收到大量的脏数据，需要使用指令替代

1. <kbd>/geyser settings</kbd> 客户端设置

    - 设置一些基岩版中仅能由服务器设置的选项，包括是否显示坐标等项目