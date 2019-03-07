						                          周五谈

Date：2018年5月26日

Topic：为什么人类喜欢玩游戏？

胡源:

牟婧妍：
      1.人类进化的过程中，游戏曾经作为人类生存技能的训练项目。
      2.人类基因中有游戏的部分。
      3.现代生活中，生存技能类的游戏已经渐渐消失，更多的是纯供娱乐的游戏。

徐若思:

张晓通:hello
hello

呼延旭东:

王志勇:

	1.人类游戏是因为人们在游戏中得到反馈/奖励/回报。
	
	2.人类游戏是因为游戏中存在获得正反馈的机会。
	
	3.从同一个游戏中，不同的人得到的反馈刺激（满足程度）是不同的，这就是为什么不同人会喜欢不同游戏
	
	4.现在电子游戏中的情节、竞技技能、故事背景设定等，使得游戏刺激多样化



Date：2018年6月1日

Topic：如果期望在一个机器人社会中自动演化出游戏，那我们该如何设计机器人


胡源:

牟婧妍：
      1.挖金矿模型可以作为参考模型进行，将研究区域分为2部分，一部分为能量获取区，一部分为娱乐区。
      2.设计机器人使其既要获取能量，也要消耗能量，以求在过程中达到平衡状态。

徐若思:

张晓通:

呼延旭东:

王志勇:

	1.人体作为一个系统，其能量的输入和输出是一个基本固定的数值。而不是依据需要消耗多少能量来
		
		这只是一个猜想的理论，如何验证这个理论？需要了解人体能量吸收和消耗的统计情况(王志勇)
		
		人体的恒温的，这需要消耗能量；（王志勇）
	
	2.游戏其实是相对于“正事”定义的，它的基本特征是：不是“正事”，但消耗能量。
	
	3.挖金矿可能是一个很好的游戏行为模型。
	
	4.在挖金矿模型中，一旦出现了不是挖金矿，但又消耗能量的行为，我们就认为游戏在机器人世界里产生了。


Date：2018年6月8日

topic：建立一个模型，模拟游戏的产生

胡源：1.相比某些冷血动物，人类利用能量的效率似乎更为低下，没有办法做到用多少吸收多少，而是必须维持一定功率运转
     2.电脑模型与真实模型都可以进行大胆设想，真实模型的具体方式是用人为参与主体，将一块区域分为两半，一个为工作区，一个为娱乐区，其中具体参数还需合理化

牟婧妍：

徐若思:

张晓通:

呼延旭东:

王志勇:
	
	1. 可以开发一个“两按钮”游戏，一个按钮产生“金币”，另一个按钮只是“无聊消遣”，规定玩家有100次点击机会，观察用户点击“消遣”按钮的情况；
	
	2. 无聊人体告诉我们赶快去消耗能量的信号。人一旦感觉到无聊，他就会去做事情来消耗能量，而他所做的这个事情不一定是挖金币。
	
	
Date：2018年6月8日

topic：三种扑克游戏的实践

      1.叫对家
      2.十点半
      3.升级

胡源：

牟婧妍：

徐若思:

张晓通:

呼延旭东:
        1.蛇、鳄鱼等爬行类动物不存在游戏的现象   能量的供给需求完全为了生存繁衍  没有多余的能量供出 
	  貌似是最合理的生存方式  然而却是一种较为低级且容错率较低的生存方式
	

王志勇:








	
Date：2018年6月20日

topic：关于一般性结构的初步猜想

呼延旭东：

--------------------------------------------
     1.游戏名称
     2.游戏者对规则进行熟悉运用
     3.阶段性取得一定结果
 -------------------------------------------- -   

张晓通：对扑克牌游戏结构的猜想

设定一个集合，集合中有{xn}n个元素，一个元素代表了一张扑克牌，如第二副牌的梅花A便是一个元素。

有y个玩家。集合内的元素根据一定的函数，将分为y个子集，这些子集互斥。

打牌的过程即使一个函数运算的过程，设规则即为一个函数fc（a,b）

c是轮数，a是自己的手牌，b是一个模糊数，代表了此轮对手的函数运行状态以及对对方的“a”的可能性之猜想。

即f（x）是对每轮出牌法的一个策略。c是有限的F（x）代表了所有的轮数的出牌状况，包括了各个时刻的abc的数值。

Q（F（x））对所有人的Fx进行某种计算（如QX=C，或者QX=Fx中的某个元素的出现次数），对Q（fx）进行排列，即分出了胜负

注1：q（fx）也可以带上轮数，最后计算总的Q（x）如升级。

注2：当存在分组时，Q的计算方法不再依靠于单个的f（x）


-------------------------------------------- -        
 
 徐若思：三种扑克游戏都有控制与被控制元素在里面，每个人都希望利用自己手中的牌控制对方以便取得主导权，但同时也在考虑是否会被还未出牌的人控制失去主导权。
 
 1.八十分：每个人每轮都有出大牌压过对手以便控制对手从而达到加分的权利，同时也有出加分牌为自己队加分的权利。（1）当该队伍占领主导权时，该玩家会想着自己队伍的牌是否够大能否继续控制住对方，如果足够大，那么出加分牌为自己队伍加分，如果不够大，想办法靠现有的能力尽可能出大牌让自己队伍占领主导权。还有一种情况时，自己队伍的牌不够大，但还是选择出加分牌，这是因为玩家心里猜测对方没有足够大的牌压过本方，心理安慰自己运气好，可以成功，但本质玩家心里仍是认为足以控制对方。
 （2）当该队伍不是主导权时，该玩家首先会想出一张大牌控制对方以便占领主导权，如果没有只好随便出一张牌划水过去。
 （3）观全大局，每个玩家都在为“控制与被控制”的问题思考利弊，最后作出决策。
 
 2.叫对家：每个玩家出牌时，都想着试图用手中的牌大过对方，以便控制对方，让自己出更多的牌能够尽早出完牌赢得胜利。另一种情况则是玩家顺水推舟，随大流走，既是自己有大牌也不出，等到适合的时机再出，这是因为每个玩家手中的牌不足以好到时时刻刻都能控制住其他人，所以等待时机，找到一个让自己手中的牌能够达到最有效控制其他人的机会，这样赢得比赛的可能性更大。
 
 3.十点半：这个游戏因为人为操作的因素很少，大部分是靠运气取得胜利，所以通过人为操作因素体现控制与被控制的表现很少。但是在玩家心里，都希望自己运气足够好，刚好手中的牌的数值尽可能接近最大值，同时猜测其他人手中的牌是否更大能够控制自己取得胜利，因此会要牌，让自己的牌更大（不超过临界值）。而对于玩家手中的牌超过临界值，却不然其他人知道，装作若无其事的样子，则同样也是让对手觉得猜测不到自己的情况、控制不到自己的心理提示，以让对手继续摸牌最终也超过临界值的目的。
 
 纵览全局，这三种游戏类似于三权分立的感觉在里面，（A有权力可以去控制B，C有权利控制A，但却又被B控制），一种环环相扣的模型，每个玩家则是其中的一个环，（在三权分立中的一个政客）在控制与被控制的环境中，找到一个平衡点，用战略的眼光让自己达到利益最大化。因此我猜想游戏就好像缩小版的模拟人类生存规则一样。
 
 
Date：2018年6月22日

Topic：就


胡源:

牟婧妍：

徐若思:

张晓通:

呼延旭东:
       1.游戏奖励机制的阶段性
       2.研究的方向是否应当调整为增加游戏可玩性的一般性结构
         在尚无法完全准确地定义游戏时，单纯讨论游戏的一般性结构是否会使无意义的游戏带来不必要的干扰
       3.无意义的游戏是否完全没有意义？
         如：正常人的撕报纸游戏（多见于老年痴呆患者）

王志勇:

Date: 2018年9月20日

Topic: 1)提出改进现有游戏的具体意见；2）讨论关于扑克游戏奖励机制的一帮性规律

胡源:

牟婧妍：

徐若思:

  奖励机制我们讨论是心理层面的东西，不太相同于游戏的一般规则可以用笔和纸进行书面表达，而我们认为奖励机制唯一评判的标准是玩家的愉悦感，只要让玩家通过游戏获取愉悦感，这便是该游戏的奖励机制。
  
  在玩牌的过程中，我们发现能够使玩家感到愉悦的事情属于
  
  1、达到最终目的，获得比赛胜利。（例如：出光所有的牌）
  
  2、在达到目的的过程中通过游戏规则来加速自己达到目的的速度 和 阻碍别人达到目的速度。（例如：斗地主中两个平民联合制约地主胜利，当然他们在制约的过程中就加速了自己的胜利，所以斗地主这套机制是一举两得。而对于某些游戏，玩家只是为了刷一套非常稀有的装备便会获得很大的愉悦感，这就是单纯为了加速自己的目的）所以我们觉得奖励机制是一个镶嵌在游戏规则里的一个东西，相辅相成，玩家在进行游戏的过程中，便达到的愉悦感，例如足球和篮球等比赛，结果固然重要，但许多人宁愿花上非常昂贵的价格看一场球却不愿意选择低廉的打开手机看结果。而对于怎么样设计游戏规则来达到好的奖励机制，还是一个有待进展的问题。 

张晓通:

呼延旭东:

王志勇：

   扑克游戏的奖励机制是一个多层嵌套的结构。
   
   
徐若思：
   在原先设计的环境中（让计算机在工作区、休息区中自我进行选择）存在一个问题：如何让计算机在不同区域中进行自我选择？我突然联想这与游戏抽奖十分相似。
例如，人们设定好不同的奖品类似与工作区、休息区的概念，而奖品的获得概率则类似与计算机在不同的区域满足的函数。当人们一按下抽奖的按钮，则之后的工作就是计算机自我选择抽出奖品。我觉得可以参考该情况”计算机是如何进行自我选择“来达到在原来设计的环境中让计算机进行自我选择。

Date: 2018年12月11日

王志勇：

    游戏是一个多分支的排序结构。对于扑克牌来说，由于牌的总数是有限的，分支越多就导致分支越短，分支越短就会极大地减少玩家出牌的可能性。
    
    举例：如下两种玩法
    
    1）每个花色是一个分支，每个分支A最小、K最大；分支之间没有关系。4个人玩，每局牌大约有90万种组合；
    
    2）每个花色7~A，8~K算一个分支；分支之间无关系。4人玩，每局牌大约有500种组合。
    
    90万：500，可见分支越短，则可能的出牌组合越少。

王志勇：

   扑克牌的一般包括以下内容：
   
   1）一个多分支排序结构
   
   2）当玩家没有该分支上的牌时，如何继续游戏的方法。
    
    
王志勇 TO 徐若思

    从下面的例子可以看出，能量和结构之间是有关系的。
    
    1）在变形金刚中，有这样的镜头，一束能量照射一块材料就产生了一个机器人。做这个镜头的人显然时觉得能量可以转化为结构。
    
    2）一个人在一个房间里设计、加工、制造出一个产品，如果我们把这个过程黑箱化，就是我们给这个房间输入能量，材料变成了结构。这也体现了能量和结构之间的映射关系。
    
    3）了解一下米勒原子汤实验，一堆无机物在放电作用下就产生了有机物，相对于无机物，有机物有明显的结构。这也给人一种能量转化为结构的图像。
    
    所以，能量和结构似乎是存在本质关系的。
    
**20190307
 
 第一周讨论
 
 张晓通 
   
   任务：阅读《扑克中的数学》。 
    
    感想：这本书前几章主要讲了gay率论的基本知识，分三章介绍了概率、期望、方差、样本、贝叶斯等基本内容。然后又讲了一部分博弈论，包括赔率以及手牌的一些概率。第三部分讲了一个模型，GTO模型。第四部分就是风险以及其他的东西。
    
    结论：这本书与我们研究的问题关系不大。里面存在几个模型也只是博弈的模型，没有什么参考价值。不过到后期的好玩性的时候兴许会用上其中的一些理论。
    
  链接：https://www.taodocs.com/p-48934651.html  The Mathematics of Poker（扑克中的数学）

*//ps：什么是gto理论。一、 什么是GTO？GTO（Game Theoretical Optimum），首先要了解这个词汇，中文直译是博弈理论最优（策略），直白点说也就是博弈论中的最优策略。那么我们如果要了解GTO，那就必须了解博弈理论。博弈论（Game Theory）本身是一门学科，而且是比较前沿的那种，这里就一笔带过，讲一些最基本的原理。用一个比较简单的定义：博弈论是二人（或者更多人）在平等的对局中各自利用对方的策略变换自己的对抗策略，达到取胜的目的。博弈论考虑游戏中的个体的预测行为和实际行为，并研究它们的优化策略。二、 纳什均衡说到博弈论，就必须得提到纳什均衡。纳什均衡是这样一种状态：博弈中的每一方都不能通过单方面改变自己的策略来增加收益。现在一些扑克pro热衷于讨论的GTO，其实就是纳什均衡的一部分。总而言之言而简之，是与出牌策略有关和我们关系不大。
