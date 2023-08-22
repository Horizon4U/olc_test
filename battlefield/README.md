MAY DO A QUICK START WITH BF.exe

————————————————————————————————————————

Tutorial

########################################

//similar control mode to the Civilization VI

***Requires manual initialization(see the samples in text.txt)

***Enter the corresponding parameters in the command line


————————————————————————————————————————

输入格式：
  第一行 M N NT NU :代表当前战场大小为 M x N ，一共有 NT 个特殊地形（除平原）， NU 个单位
  接下来 NT 行特殊地形信息，每行格式为 R C T ，代表在 (R,C) 坐标有一个地形为 T 。 T = W 代表
  深水( WATER )， T = M 代表高山( MOUNTAIN )， T = F 代表森林( FOREST )。
  接下来 NU 行代表单位信息，每行格式为 R C S U ，代表在 (R,C) 坐标有一个类型为 U 的单位。其
  中 U = FT 代表步兵， U = KN 代表骑士。 S = A 代表该单位为 Player A 的单位， S = B 代表该
  单位为 Player B 的单位。
  
可能因为地图格式错误无法装载，没有写报错机制

我们规定地图的大小不超过 20 x 20

任何单位如果出现在不可逾越的地形上将被立刻消灭。 不可逾越的地形包括深水、高山、以及深渊。


————————————————————————————————————————


Press left mouse button to select the unit
Press right mouse button to control the unit //move		attack		cast spells
Press SPACE to start a new turn

按空格交换回合

ctrl+A全选复制text4.txt中文本，复制到命令行中，按enter后开始


————————————————————————————————————————



Knight : Genji, Reinhardt

  5移动力，左键选中，右键攻击或移动，只可近战攻击


————————————————————————————————————————
  

Footman : Doomfist, Orisa

  4移动力，左键选中，右键攻击或移动，只可近战攻击


————————————————————————————————————————

  

Archer : Widowmaker ,Hanzo

  3移动力，左键选中，右键攻击或移动，攻击范围为两格（圆环），不可近身攻击



————————————————————————————————————————
  

Mage : Moira, Mercy

  2移动力，左键选中，右键移动，不可直接攻击，只可施放法术，
  
  选中时英文输入下按f为火球术模式，按e为地震术模式，选中时按ctrl可退出施放法术模式进行移动
  
  火球术选中范围为周围一圈内燃烧树
  
  地震术选中范围为周围三圈内把山变成平原，把平原和森林变成深渊，深渊自动被附近深水填满
  
  ————————————————————————————————————————

森林移动消耗2移动力，平原移动消耗1移动力，山和水不可移动

########################################
