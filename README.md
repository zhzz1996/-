# -
# 人生管理系统 (Life Management System)

## 概述
- 高情商：本系统通过游戏化方法，帮助用户以有趣方式管理日常生活。
- 低情商：帮助玩家在无聊且迷茫的人生中打发时间，避免腐烂。

## 系统组成

### 看板
- 功能展示：包括称号系统、奖励点、成就等级等。
- 数据跟踪：例如任务完成、学习时长、健身时长。
- ![看板](https://pan.baidu.com/s/1BKODb6C3-73Vc_MGuVouTA?pwd=ok0z)

### 任务信息表
任务信息表主要负责发布任务及相应奖励。本系统会适时发布任务，包括常规任务、限时任务和紧急任务等，不同的任务对应不同的奖励。其中，常规任务是周期性的，如每天坚持早睡早起，坚持早晚刷牙，坚持健身等等，其目的在于保持表面上的良好生活态度，帮助玩家不至于因为摆烂而腐烂。限时任务是有时间限制的，如完成一个项目，写好一篇论文等，其目的在于调动玩家面对人生的主动性，帮助玩家不至于因为摆烂而什么都不干。紧急任务是突发性的，如今天被领导骂了，心情郁闷至极无处发泄，可以通过完成紧急任务来实现精神胜利等。每当完成一个任务，需要在备注栏输入“已完成”，奖励就会自动发放至看板。举例如下：
| 时间       | 任务名称  | 内容                 | 奖励点 | 成就 |
|------------|-----------|----------------------|--------|------|
| 2024/1/16  | 早睡早起  | 8点起床，23点睡觉    | 10     | -    |
| 2024/1/17  | 学习      | 完成一个C++项目      | 100    | E    |
| 2024/1/18  | 忍辱负重  | 被领导PUA，心情不爽  | 200    | D    |

### 奖励系统
本系统的奖励分为两种：奖励点和成就。其中，奖励点反映了任务的稀缺性，越是稀缺的任务，奖励点越高，比如坚持每天健身奖励10点，写完一篇论文奖励200点。因为健身每天都可以做，而完成论文需要一个比较长的周期，所以奖励点会有所不同。同时，为了和现实世界接轨，丰富系统的含金量，奖励点与RBM的汇率为1:1。成就反映了任务的难度，还是以健身和写论文为例，健身一次的难度很低，有手有脚肯动就行，所以不会发放成就，而写完一篇论文的难度较大，可以发放成就。为了更好地界定任务的难度来发放成就，本系统将成就等级与奖励点，也就是RBM进行挂钩，对应关系如下：
| 成就等级 | 奖励点 |
|--|--|
| E级 | 250点 |
| D级 | 500点 |
| C级 | 1000点 |
| B级 | 2000点 |
| A级 | 4000点 |

举例而言，E级成就的难度为250奖励点，也就是说，只要是250块钱能解决的任务，所发放的成就不得超过E级，其他级别以此类推。

### 商城
商城模块是本系统的另一大重要模块，在完成任务后所发放的奖励点和成就可在商城进行消费，举例如下：
| 时间       | 名称  |奖励点 | 成就 | 备注 |
|------------|-----------|--------|------|------|
| 2024/1/18  | 买iPod nano3  | 490    | D     | 已兑换    |
| 2024/1/20  | 烧烤      | 123      | E    | 已兑换    |
在商城中，所有玩家想要的东西都可以作为商品进行兑换，为了避免刷分，如每天啥都不干，就刷个牙挣10奖励点，连续100天攒下1000奖励点然后买个大的，这种行为就违背了本系统管理人生的初衷，毕竟人活着不能除了刷牙啥都不做。所以本系统规定，商城中的所有商品都需要有相应的成就才可兑换。举例而言，吃一顿烧烤花了123块钱，除了会扣除123奖励点之外，还会消耗E级成就一项。同时因为E级成就对应的奖励点为250点，扣除本次的123点之后还剩余127点的额度，所以你明天再吃一顿火锅的时候就只需要扣除奖励点，不需要再消耗成就了。在兑换完商品之后，需要在备注栏输入“已兑换”，看板会自动扣除相应的奖励点和成就。
### 称号系统
为了加强玩家的荣誉感，本系统增加了称号系统，灵感来源于斗破苍穹，为不同的分数段设置不同的称号，分数的计算公式为：奖励点+所拥有成就对应的奖励点。对斗破苍穹不感兴趣的玩家可在称号工作表自行设置称号。

### 其他
计数区等图表主要是用来记录玩家的各项指标，以增加玩家的成就感，各位玩家可根据自己的实际情况进行设置。


## 声明
本系统的最终解释权归本人所有，如有少许雷同，说明我们有缘。同时也欢迎各位玩家对本系统进行魔改，~~让我看看你们的XP~~，并分享出来让大家一起摆烂。
最后祝各位玩家都能找到人生的意义，一边摆烂一边积极的活下去。

## 致谢及灵感来源
- Playtask
- 无限恐怖
- 斗破苍穹
- 美团骑手奖励规则
