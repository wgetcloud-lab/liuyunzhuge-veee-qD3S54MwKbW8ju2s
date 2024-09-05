
# 代码整洁之道


![image-20240904225436374](https://img2023.cnblogs.com/blog/3292471/202409/3292471-20240904225444350-116460863.png)


## 简介：


本书是编程大师“Bob 大叔”40余年编程生涯的心得体会的总结，讲解要成为真正专业的程序员需要具备什么样的态度，需要遵循什么样的原则，需要采取什么样的行动。作者以自己以及身边的同事走过的弯路、犯过的错误为例，意在为后来者引路，助其职业生涯迈上更高台阶。


本书适合所有程序员阅读，也可供所有想成为具备职业素养的职场人士参考。


## 第一章：专业主义


在开启阅读此书之前，不免先问一下自己一个问题，根据这个问题的回答来决定对此书阅读的态度。


你想成为一名“专业人士”吗？你确实是想成为专业的软件工程师，对吗？


如果坚定地回答道\-\-\-“是\-\-\-\-\-！”，那么调整好状态聆听Bob大叔对他40多年的编程经历的娓娓道来吧\~


### 1\.1 清楚你要什么


如果你想成为一名专业人士，必须要承担责任。


“专业主义”不仅仅象征着荣誉与骄傲，而且明确意味着责任与义务。


从你无法负责的事情上不可能获得荣誉和骄傲。


### 1\.2 承担责任


**没有对例行程序进行测试就交付软件是不负责任的。**


Bob大叔担任一款控制软件的“负责工程师”，所负责的软件控制一个测量电话线路质量的小型机系统和危机系统，程序是用汇编语言编写的。该系统每天晚上都会运行“夜间例行程序”来对线路进行检测，而bob为了使新功能如期发布，未经测试直接将新系统程序交付给用户，结果接连修复程序bug。给用户和经理造成损失。


**如何承担责任？**


### 1\.3 首先，不行损害之事


#### 1\.3\.1 不要破坏软件功能


无法开发出完美的程序，那么要对自己的不完美负责。


所谓专业人士，就是能对自己犯下的错误负责的人，哪怕那些错误实际上在所难免。


所以我们要练习的第一件事情就是“道歉”，尽管是必要的，但是仅仅如此还不够。不能一而再，再而三地犯相同的错误。


职业经验多了之后，你的失误率应该快速减少，甚至渐近于零。失误率永远不可能等于零，但你有责任让它无限接近零。


这里给出具体的表现：


1. 让QA找不出任何问题
2. 要确信代码正常运行


对所写的代码内容要做到100%的测试，但是有些代码不是很难测试吗？是的，但之所以很难测试，是因为设计时就没考虑如何测试。唯一的解决办法就是要设计易于测试的代码，最好是先写测试，再写要测的代码，这一方法叫做**测试驱动开发（TDD）**。
3. 自动化QA


作为开发人员，你需要有个相对迅捷可靠的机制，以此判断所写的代码可否正常工作，并且不会干扰系统的其他部分。因此，你的自动化测试至少要能够让你知道，你的系统很有可能通过QA的测试。


### 1\.3\.2不要破坏结构


成熟的专业开发人员知道，聪明人不会为了发布新功能而破坏结构。


结构良好的代码更灵活。以牺牲结构为代价，得不偿失，将来必追悔莫及。


所有软件项目的根本指导原则是，软件要易于修改。如果违背这条原则搭建僵化的结构，就破坏了构筑整个行业的经济模型。


要想证明软件易于修改，唯一办法就是做些实际的修改。


该在什么时候做这些简单的小修改呢？随时！关注哪个模块，就对它做点简单的修改来改进结构。每次通读代码的时候，也可以不时调整一下结构。


如果觉得修改之后重新测试很麻烦，那就体现掌握测试方法的重要性了。


### 1\.4 职业道德


职业发展是你自己的事。雇主没有义务确保你在职场能够立于不败之地，也没义务培训你，送你参加各种会议或给你买各种书籍充电。这些都是你自己的事。将自己的职业发展寄希望于雇主的软件开发人员将会很惨。


你应该计划每周工作60小时。前40小时是给雇主的，后20小时是给自己的。在这剩余的20小时里，你应该看书、练习、学习，或者做其他能提升职业能力的事情。


*或许你不愿那么勤勉。没问题。只是那样的话你也不能自视为专业人士了，因为所谓“术业有专攻”那也是需要投入时间去追求的。*


* #### 了解你的领域


总的来说，那些在过去50年中来之不易的理念，绝大部分在今天仍像过去一样富有价值，甚至宝贵了。


​ 下面列出了每个专业软件开发人员必须精通的事项：


* **设计模式**。必须能描述GOF书中的全部24种模式，同时还要有POSA书中的多数模式的实战经验。
* **设计原则**。必须了解SOLID原则，而且要深刻理解组件设计原则。
* **方法。**必须理解XP、Scrum、精益、看板、瀑布、结构化分析及结构化设计等。
* **实践**。必须掌握测试驱动开发、面向对象设计、结构化编程、持续集成和结对编程。
* **工件。**必须了解如何使用UML图、DFD图、结构图、Petri网络图、状态迁移图表、流程图和决策表。
* #### 坚持学习


读书，看相关文章，关注博客和微博，参加技术大会，访问用户群，多参与读书与学习小组。不懂就学，不要畏难。如果你是.NET程序员，就去学学Java；如果你是Java程序员，就去学学Ruby；如果你是C语言程序员，就去学学Lisp；如果你真想练练脑子，就去学学Prolog和Forth吧！
* #### 练习


业精于勤。真正的专业人士往往勤学苦干，以求得自身技能的纯熟精炼。只完成日常工作是不足以称为练习的，那只能算是种执行性质的操作，而不是练习。练习，指的是在日常工作之余专门练习技能，以期自我提升。


作者这里指出“卡塔”类型练习，类似刷leetcode解决小的单元问题。
* #### 合作


专业软件开发人员往往会更加努力地尝试与他人一起编程、一起练习、一起设计、一起计划，这样他们可以从彼此身上学到很多东西，而且能在更短的时间内更高质量地完成更多工作。
* #### 辅导


想迅速牢固地掌握某些事实和观念，最好的办法就是与你负责指导的人交流这些内容。这样，传道授业的同时，导师也会从中受益。
* #### 了解业务领域


每位专业软件开发人员都有义务了解自己开发的解决方案所对应的业务领域。如果编写财务系统，你就应该对财务领域有所了解；如果编写旅游应用程序，那么你需要去了解旅游业。你未必需要成为该领域的专家，但你仍需要用功，付出相当的努力来认识业务领域。
* #### 与雇主/客户保持一致


雇主的问题就是你的问题。你必须弄明白这些问题，并寻求最佳的解决方案。每次开发系统，都应该站在雇主的角度来思考，确保开发的功能真正能满足雇主的需要。
* #### **谦逊**


编程是一种创造性活动。写代码是无中生有的创造过程，我们大胆地从混沌之中创建秩序。我们自信地发布准确无误的指令，稍有差错，机器的错误行为就可能造成无法估量的损失。因此，编程也是极其自负的行为。


然而，专业人士也知道自己会摔跟头，自己的风险评估也有出错的时候，自己也有力不从心的时候。这时候，如果他们照照镜子，会看到那个自负的傻瓜正对着自己笑。


因此，在发现自己成为笑柄时，专业人士会第一个发笑。他从不会嘲讽别人，自作自受时他会接受别人的嘲讽。反之，他则会一笑了之。他不会因别人犯错就对之横加贬损，因为他知道，自己有可能就是下一个犯错的人。


 本博客参考[wgetCloud机场](https://tabijibiyori.org)。转载请注明出处！
