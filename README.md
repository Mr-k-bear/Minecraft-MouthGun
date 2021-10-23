
我的世界，但是你的嘴变成了武器!
Minecraft, but your mouth becomes a weapon!

# 要点

1. 插件将检测玩家麦克风音量的大小。
2. 当玩家麦克风有声音时将蓄力一个射弹。
3. 当声音达到设定的最大值时将射弹发射。
4. 射弹的强度受到蓄力程度的影响。
5. 射弹有很多种类且每次随机发射。
6. 种类和概率参见下方"发射物概率列表"。
7. 被射弹击杀的生物算作玩家击杀。

# Main point

1. The plugin will detect the player's microphone volume.
2. When the player's microphone has a sound, a projectile will be charged.
3. Launch the projectile when the sound reaches the set maximum.
4. The strength of the projectile is affected by the degree of charge.
5. There are many types of projectiles and they are randomly fired every time.
6. For types and probabilities, please refer to the "List of Projectile Probabilities" below.
7. Mobs killed by projectiles are counted as player kills.

# 项目结构

1. 版本要求：客户端Fabric-1.17.1、服务端Spigot1.17.1。
2. 此插件由三个部分组成：
3. Fabric 模组 (VoiceLibrary-1.0.0.jar) 用于与服务器通信。
4. Python 独立程序 (main.exe) 用于音频采集。
5. Spigot 插件 (MouthGunBukkit.jar) 全部玩法的主逻辑。

# Project structure

1. Version requirements: Fabric-1.17.1 on the client side, Spigot-1.17.1 on the server side.
2. This plugin consists of three parts:
3. The Fabric module (VoiceLibrary-1.0.0.jar) is used to communicate with the server.
4. Python standalone program (main.exe) for audio capture.
5. Spigot plug-in (MouthGunBukkit.jar) The main logic of all gameplay.

# 使用方法

1. 安装 Spigot 插件，并开启服务端。
2. 安装 Fabric 插件，启动客户端，但是不要立刻加入服务器。
3. 启动 Python 独立程序，如果启动失败尝试删除生成的 "config.txt" 重试。
4. 客户端加入服务器，运行 "/start" 指令。
5. 使用 "/setting" 指令进行音量校准。
6. 正式开始游戏。

# Instructions

1. Install the Spigot plug-in and start the server.
2. Install the Fabric plug-in, start the client, but do not join the server immediately.
3. Start the Python standalone program, if the startup fails, try to delete the generated "config.txt" and try again.
4. The client joins the server and runs the "/start" command.s
5. Use the "/setting" command to calibrate the volume.

# 发射物概率列表

1. 随机药水箭矢 64.8%
2. 恶魂的烈焰弹 10%
3. 末影龙的龙息 10%
4. 普通的鸡蛋 5%
5. 普通的雪球 5%
6. 爆炸箭 5%
7. 附魔金苹果 (彩蛋) 0.2%

# List of Projectile Probabilities

1. Random Potion Arrow 64.8%
2. Ghast's Fireball 10%
3. Dragon Breath of Ender Dragon 10%
4. Ordinary eggs 5%
5. Ordinary snowball 5%
6. Explosive Arrow 5%
7. Enchanted Golden Apple (Easter Egg) 0.2%

# 作者 (Author)

玩法逻辑 (Play logic): @MrKBear
声音检测 (Sound detection): @wzp2-
插件测试 (Plug-in test): @尹蕤呀と日暮里

# Message from the author @MrKBear
如果你要使用此插件制作视频，我默认授权，不过请附上此页面链接，谢谢~
If you want to use this plugin to make a video, I authorize it by default, but please attach a link to this page, thanks~
