# aircraft-warfare
python代码实现飞机大战

# 解释
游戏界面如下图所示
游戏的基本设定:

- 敌方共有大中小3款飞机，分为高中低三种速度;

- 子弹的射程并非全屏,而大概是屏幕长度的80%;

- 消灭小飞机需要1发子弹,中飞机需要8发,大飞机需要20发子弹;
- 每消灭一架小飞机得1000分,中飞机6000分,大飞机10000分;

- 每隔30秒有一个随机的道具补给,分为两种道具，全屏炸弹和双倍子弹;

- 全屏炸弹最多只能存放3枚,双倍子弹可以维持18秒钟的效果;

- 游戏将根据分数来逐步提高难度,难度的提高表现为飞机数量的增多以及速度的加快。

- 另外还对游戏做了一些改进,比如为中飞机和大飞机增加了血槽的显示,这样玩家可以直观地知道敌机快被消灭了没有;我方有三次机会,每次被敌人消灭,新诞生的飞机会有3秒钟的安全期;游戏结束后会显示历史最高分数。

这个游戏加上基本的注释代码量在800行左右,代码看上去比较多，多打代码少动脑。所以大家不要怕,越是多的代码,逻辑就越容易看得清楚，就越好学习。好,那让我们从无到有,从简单到复杂来一起打造这个游戏吧!

# 代码
myplane.py：我方飞机

enemy.py：敌方飞机

bullet.py：子弹的定义

supply.py：发放补给包

飞机大战.py：主模块