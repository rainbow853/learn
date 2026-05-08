# Laws of Software Engineering 软件工程定律
## Architecture 架构
### Hyrum's Law  海伦姆定律
With a sufficient number of API users, all observable behaviors of your system will be depended on by somebody.   
当 API 用户数量足够多时，你系统的所有可观察行为都将受到某些用户的依赖。
![./hyrums-law.png](hyrums-law.png)
> sufficient 足够的；充分的   

### Gall's Law  加尔定律
A complex system that works is invariably found to have evolved from a simple system that worked.   
一个运转良好的复杂系统，无一例外都是由一个运转良好的简单系统演变而来。
![./galls-law.png](galls-law.png)

### The Law of Leaky Abstractions 抽象泄漏定律
All non-trivial abstractions, to some degree, are leaky.   
所有非平凡的抽象在某种程度上都是有缺陷的。
![./leaky-abstractions.png](leaky-abstractions.png)
> trivial 琐碎的；微不足道的；无意义的   

### Tesler's Law (Conservation of Complexity) 泰斯勒定律（复杂性守恒定律）
Every application has an inherent amount of irreducible complexity that can only be shifted, not eliminated.   
每个应用程序都存在一定程度的固有复杂性，这种复杂性只能转移，而不能消除。  
![./tesler-law.png](tesler-law.png)

### CAP Theorem  CAP 定理
A distributed system can guarantee only two of: consistency, availability, and partition tolerance.
分布式系统只能保证以下三者中的两项：一致性、可用性和分区容错性。   
![./CAP-theorem.png](CAP-theorem.png)
> guarantee  确保；保证   

### Second-System Effect  第二系统效应
Small, successful systems tend to be followed by overengineered, bloated replacements.   
小型、成功的系统之后，往往会出现过度设计、臃肿的替代系统。
![./second-system-effect.jpeg](second-system-effect.jpeg)
> bloated 肿胀的；臃肿的；庞大的

### Fallacies of Distributed Computing 分布式计算的谬误
A set of eight false assumptions that new distributed system designers often make.   
新手分布式系统设计者常犯的八个错误假设。
![./fallacies-of-distributed-computing.png](fallacies-of-distributed-computing.png)
> 网络可靠
> 延迟为零
> 带宽无限
> 网络是安全的
> 拓扑结构不变
> 只有一个管理员
> 运输成本为零
> 网络是同质的

### Law of Unintended Consequences 意料之外的后果定律
Whenever you change a complex system, expect surprise.   
当你改变一个复杂的系统时，要做好应对意外情况的准备。
![./law-of-unintended-consequences.png](law-of-unintended-consequences.png)
> The Law of Unintended Consequences is often seen as a simple system that tries to regulate a complex system.   
> 非预期后果定律通常被视为一个试图调节复杂系统的简单系统。

### Zawinski's Law  扎温斯基定律
Every program attempts to expand until it can read mail.   
每个程序都会尝试扩展，直到能够读取邮件为止。
![./zawinski-law.png](zawinski-law.png)


## Teams 团队
### Conway's Law 康威定律
Organizations design systems that mirror their own communication structure.   
组织会设计与自身沟通结构相呼应的系统。
![./conways-law.png](conways-law.png)

### Brooks's Law 布鲁克斯定律
Adding manpower to a late software project makes it later.  
给一个已经延期的软件项目增加人手只会让项目延期。
![./brooks-law.png](brooks-law.png)

### Dunbar's Number 邓巴数
There is a cognitive limit of about 150 stable relationships one person can maintain.   
一个人能够维持的稳定关系数量存在认知极限，大约为150个。
![./dunbar-number.png](dunbar-number.png)
> cognitive 认知的   

### The Ringelmann Effect 林格尔曼效应
Individual productivity decreases as group size increases.   
随着群体规模的增大，个人生产力会下降。
![./ringelmann-effect.png](ringelmann-effect.png)
> coordination overhead 协同开销  
> motivation drop 动力下降 

### Price's Law 普莱斯定律
The square root of the total number of participants does 50% of the work.   
参与者总数的平方根完成了 50% 的工作。
![./prices-law.png](prices-law.png)
> assymetrical 不对称的   

### Putt's Law 普特定律
Those who understand technology don't manage it, and those who manage it don't understand it.   
懂技术的人不擅长管理技术，而擅长管理技术的人却不了解技术。
![./putts-law.png](putts-law.png)

### Peter Principle 彼得原理
In a hierarchy, every employee tends to rise to their level of incompetence.   
在等级制度中，每个员工往往都会晋升到自己不胜任的级别。
![./peter-principle.png](peter-principle.png)

### Bus Factor 巴士因素
The minimum number of team members whose loss would put the project in serious trouble.   
团队中至少需要失去多少名成员才会使项目陷入严重困境。
![./bus-factor.png](bus-factor.png)

### Dilbert Principle 迪尔伯特原理
Companies tend to promote incompetent employees to management to limit the damage they can do.   
公司往往会提拔不称职的员工担任管理层，以减少他们可能造成的损失。
![./dilbert-principle.png](dilbert-principle.png)


## Planning 规划
### Premature Optimization (Knuth's Optimization Principle) 过早优化（克努特优化原理）
Premature optimization is the root of all evil.   
过早优化是万恶之源。
![./premature-optimization.png](premature-optimization.png)
> velocity 速度   

### Parkinson's Law 帕金森定律
Work expands to fill the time available for its completion.   
工作量会不断增加，直至填满所有可用的完成时间。
![./parkinson-law.png](parkinson-law.png)

### The Ninety-Ninety Rule 九九十法则
The first 90% of the code accounts for the first 90% of development time; the remaining 10% accounts for the other 90%.   
前 90% 的代码占用了前 90% 的开发时间；剩下的 10% 占用了另外 90% 的开发时间。
![./90-90-rule.png](90-90-rule.png)

### Hofstadter's Law 霍夫斯塔特定律
It always takes longer than you expect, even when you take into account Hofstadter's Law.   
即使考虑到霍夫斯塔特定律，实际花费的时间也总是比你预期的要长。
![./hofstadter-law.png](hofstadter-law.png)

### Goodhart's Law 古德哈特定律
When a measure becomes a target, it ceases to be a good measure.   
当一项指标成为目标时，它就不再是一项好的指标了。
![./goodharts-law.png](goodharts-law.png)
> cease 停止；终止   

### Gilb's Law 吉尔布定律
Anything you need to quantify can be measured in some way better than not measuring it.   
任何需要量化的事物，总有一种方法可以测量，而且这种方法比不测量要好。
![./gilbs-law.png](gilbs-law.png)


## Quality 质量
### The Boy Scout Rule 童子军规则
Leave the code better than you found it.   
让代码比你最初发现它时更好。
![./boy-scout-rule.png](boy-scout-rule.png)

### Murphy's Law / Sod's Law 墨菲定律/索德定律
Anything that can go wrong will go wrong.   
凡事皆有可能出错，而且一定会出错。
![./murphy-law.png](murphy-law.png)

### Postel's Law 波斯特尔定律
Be conservative in what you do, be liberal in what you accept from others.   
做事要保守，接受别人的东西要开明。
![./postels-law.png](postels-law.png)

### Broken Windows Theory 破窗理论
Don't leave broken windows (bad designs, wrong decisions, or poor code) unrepaired.   
不要让破损的窗户（糟糕的设计、错误的决策或低劣的代码）得不到修复。
![./broken-window-theory.png](broken-window-theory.png)

### Technical Debt 技术债务
Technical Debt is everything that slows us down when developing software.   
技术债务是指在软件开发过程中拖慢我们速度的一切因素。
![./technical-debt.png](technical-debt.png)

### Linus's Law 莱纳斯定律
Given enough eyeballs, all bugs are shallow.   
只要有足够的人关注，所有的虫子都会变得浅薄。
![./linus-law.png](linus-law.png)

### Kernighan's Law 克尼根定律
Debugging is twice as hard as writing the code in the first place.   
调试的难度是编写代码的两倍。
![./kernighan-law.png](kernighan-law.png)

### Testing Pyramid 测试金字塔
A project should have many fast unit tests, fewer integration tests, and only a small number of UI tests.   
一个项目应该有很多快速的单元测试，较少的集成测试，以及少量的 UI 测试。
![./testing-pyramid.png](testing-pyramid.png)

### Pesticide Paradox 农药悖论
Repeatedly running the same tests becomes less effective over time.   
反复进行相同的测试，随着时间的推移，效果会越来越差。
![./pesticide-paradox.png](pesticide-paradox.png)

### Lehman's Laws of Software Evolution 雷曼软件演化定律
Software that reflects the real world must evolve, and that evolution has predictable limits.   
反映现实世界的软件必须不断发展，而这种发展是有可预见的局限性的。
![./lehman-laws.png](lehman-laws.png)
> (1)持续变化 (2)日益复杂 (3)自我调节 (4)组织稳定性 (5)熟悉度 (6)持续增长 (7)质量下降 (8)反馈系统

### Sturgeon's Law 斯特金定律
90% of everything is crap.  
90%的东西都是垃圾。
![./sturgeon-law.png](sturgeon-law.png)


## Scale 规模
### Amdahl's Law 阿姆达尔定律
The speedup from parallelization is limited by the fraction of work that cannot be parallelized.   
并行化带来的加速效果受限于无法并行化的工作比例。
![./amdahl-law.png](amdahl-law.png)

### Gustafson's Law 古斯塔夫森定律
It is possible to achieve significant speedup in parallel processing by increasing the problem size.   
通过增加问题规模，可以显著提高并行处理的速度。
![./gustafson-law.png](gustafson-law.png)

### Metcalfe's Law 梅特卡夫定律
The value of a network is proportional to the square of the number of users.   
网络的价值与用户数量的平方成正比。
![./metcalfe-law.png](metcalfe-law.png)
> proportional 与...成比例的


## Decisions 决策
### Dunning-Kruger Effect  邓宁-克鲁格效应
The less you know about something, the more confident you tend to be.   
对某件事了解得越少，往往就越自信。
![./dunning-kruger-effect](dunning-kruger-effect.png)
> peak 顶峰 naivety 天真   
> valley 山谷 impostor 骗子   
> plateau 高原 maturity 到期；成熟度

### Hanlon's Razor  汉隆剃刀
Never attribute to malice that which is adequately explained by stupidity or carelessness.   
永远不要把可以用愚蠢或粗心大意解释的事情归咎于恶意。
![./hanlons-razor](hanlons-razor.png)
> malice 恶意；恶意   
> He acted out of malice.他出于恶意行事。   
> adequately 充分地；足够地   
> She explained the issue adequately   
> incompetence 无能力；不胜任   
> Due to incompetence, the project was delayed.由于无能力，项目被延误了

### Occam's Razor  奥卡姆剃刀
The simplest explanation is often the most accurate one.   
最简单的解释往往是最准确的。
![./occams-razor](occams-razor.png)

### Sunk Cost Fallacy  沉没成本谬误
Sticking with a choice because you've invested time or energy in it, even when walking away helps you.   
即使放弃对你更有利，但因为你已经投入了时间和精力，所以仍然坚持自己的选择。
![./sunk-cost-fallacy](sunk-cost-fallacy.png)
> stick 坚持；粘附   
> He was sticking to the plan.他坚持按计划行事。   
> invest 投资   
> He invested in the stock market.他在股市投资了。

### The Map Is Not the Territory 地图并非疆域本身
Our representations of reality are not the same as reality itself.   
我们对现实的认知与现实本身并不相同。
![./map-is-not-territory.png](map-is-not-territory.png)

### Confirmation Bias  确认偏差
A tendency to favor information that supports our existing beliefs or ideas.   
倾向于选择支持我们现有信念或想法的信息。
![./confirmation-bias.png](confirmation-bias.png)

### The Hype Cycle & Amara's Law 炒作周期与阿马拉定律
We tend to overestimate the effect of a technology in the short run and underestimate the impact in the long run.   
我们往往高估一项技术在短期内的影响，而低估其在长期内的影响。
![./gartner-cycle.png](gartner-cycle.png)
> hype 过度炒作；狂热  
> The tech industry is full of hype.科技行业充满了炒作。

### The Lindy Effect  林迪效应
The longer something has been in use, the more likely it is to continue being used.   
某物使用时间越长，就越有可能继续被使用。
![./the-lindy-effect.jpg](the-lindy-effect.jpg)

### First Principles Thinking 第一性原理思维
Breaking a complex problem into its most basic blocks and then building up from there.   
将复杂问题分解成最基本的部分，然后从这些基本部分入手解决问题。
![./first-principles-thinking.png](first-principles-thinking.png)

### Inversion 倒置
Solving a problem by considering the opposite outcome and working backward from it.   
通过考虑相反的结果并从中反向推导来解决问题。
![./inversion.png](inversion.png)

### Pareto Principle (80/20 Rule) 帕累托法则（80/20 法则）
80% of the problems result from 20% of the causes.   
80%的问题是由20%的原因造成的。
![./pareto-principle.png](pareto-principle.png)

### Cunningham's Law  坎宁安定律
The best way to get the correct answer on the Internet is not to ask a question, it's to post the wrong answer.   
在互联网上获得正确答案的最佳方法不是提问，而是发布错误答案。
![./cunningham-law.png](cunningham-law.png)
