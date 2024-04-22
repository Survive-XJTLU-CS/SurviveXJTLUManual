---
description: Edit by LeslieXu
---

# 西浦Y3课程

我校ics的课程涵盖还是比较标准的，基本的计算机核心课都有了，申请研究生肯定是足够的。但是如果是希望自己能够从事一些开发工作或者是科研访学，这些课程是远远不够的，可以说如果仅仅学课内课程的话什么活也干不了（非常抽象），更别说有些课的质量实在是一言难尽。这篇会分享ics基本的核心课信息+一点网课推荐。作者是20级的，所以是根据20级的课设和lecturer写的，后续有可能会做出调整，但大体不会改变。

## Y3-S1

#### CAN201 Introduction to Networking

Delivered by: Dr. Fei Chen and Dr. Enjun Fan

Programming Language: Python&#x20;

Workload：★★★☆☆ (3/5) 课程收获: ★★★★☆ (4/5)

这门课在20级之前应该都是Fei Chen一个人带的，19级的cw据说很难，给了一个diy的protocol然后手搓C/S，我校为数不多的还可以的coding exercise，评分标准是按传输文件的速度，完全符合正态分布，被卷成麻花，report基本不看，后来据说惨遭投诉课程难度下降(cw难度被腰斩了)。分数结构上cw的占比很高(40%)，和期末(45%)差不多。有百分之15是lab课白送的，基本只要上了lab就能拿满。学期初还说要考勤，搞得人心惶惶的，结果每节课都有录播，不用去lab，看完录播课提交每周的assignment就可以拿满15分。在期中之前的lecture是Fei Chen讲的，后半学期则是Wenjun Fan。&#x20;

课程结构直接是照抄的[Computer Networking: A Top-Down Approach](https://gaia.cs.umass.edu/kurose\_ross/index.php)。非常经典的计算机网络课程，进度非常快，讲课进度和umass官方提供的视频课程差不多，个人感觉跟着这个进度是吃不透这门课的。如果想找替代课程的同学，推荐观看[中科大计算机网络](https://www.bilibili.com/video/BV1JV411t7ow/)。课程时长比较恐怖，2小时只讲我校一半lecture的东西，不做多赘述，自行观看。 有关cw：20届的cw变成了groupwork，并且分为了两个part，每个part判分分为code和report两个部分。Pt.1是阉割版本的19cw，给定了protocol和server文件，只要求完成对应的client文件，难度急剧下降。Pt.2是实现根据OpenFlow protocol的SDN重定向流量，还是比较有意思的，虽然实现功能只要在OPF1.3的基础上多加几行代码，但是要看懂SDN控制器的工作流程需要花一点时间，作者猛看OFP文档才找到了对应的API，最抽象的是下一节lab直接把答案需要使用的API讲出来了。由于难度被阉割，所以每一组的判分不会很悬殊，甚至变成了report大赛。

#### CPT 203 Software Engineering

Delivered by: Soon Phei Tin&#x20;

Programming Language: Java&#x20;

Workload：★☆☆☆☆ (1/5) 课程收获: ★☆☆☆☆ (1/5)

这门课可能会让很多同学失望的一门课，非常非常非常traditional的SE课程，PPT都快包浆了，课程也很无聊，作者只上了第一节lecture就再也没有去过了。同许多老旧软件工程课一样强调各种类图、文档设计、测试，大部分都是概念类的知识，猛猛背书就完事了。

Lecture讲课昏昏欲睡，感觉水平也不是很好，没有学到practical的东西。唯二涉及到一定代码的可能是高内聚低耦合部分会讲一点java代码的类设计还有是junit test。（很少）要拿分重中之中是时序图，类图，活动图，类图等图的设计和绘画，建议自己多使用visual paradigm等软件或者手画一下，期末时候占比很重。 两个Assessment也是纯文字的选择，很水很水，而且答案玄学。 希望这门课能早点改掉吧，能学到东西的部分真的很少。

#### CPT 205 Computer Graphics

Delivered by: Yong Yue 

Programming Language: C++

Workload：★★★☆☆ (3/5) （如果很卷的话 cwworkload可以做的很大） 课程收获: ★★★☆ (3/5)&#x20;

&#x20;这一门课和DB是俩门选修课，二选一，如果想走游戏引擎或者游戏客户端开发的同学可以选这门课。(然而并没有什么很大用处) 岳老板常年沉淀过的课，对于图形学的intro课来说，理论内容应该算是面面俱到：从一开始的基础线性代数，变换矩阵，渲染管线，建模（这一部分感觉有的知识比较多余），光照和材质，纹理映射等。理论内容还是很多的。PPT依旧包浆，像Ray tracing之类的知识没有涉及到。岳老板可能年纪大了，lecture都感觉一直在念ppt，昏昏欲睡。Lab给的sample code还是挺有用的，值得看看，对完成两个coursework很有帮助。Lec内容和Lab内容可能有点割裂，lec纯理论，结尾时候会讲解几个OpenGL的API，lab的话就是给了基于OpenGL的samplecode，去看一些理论的简单运用。&#x20;

Coursework：两个，一个是2D，一个是3D。两个都是基于OpenGL的，两个都是基于Freeglut库的，应该只能使用STL和freeglut俩Cpp的库，不给使用多余的库。第一个cw公布的时间在前半学期，能用到的知识比较少，基本只有画一些基本图形和几何变化，可以做的很卷，美工大赛。第二个3d作业也是用openGL搭建场景，可以运用到光照，纹理映射的知识了。有认识的同学做的很卷很卷。很像美术创意大赛，做的好看应该分数就不错。个人觉得有点不太合理 如果想要自己深入学习图形学的同学，可以先看看闫神的[GAMES101](https://www.bilibili.com/video/BV1X7411F744/?spm\_id\_from=333.337.search-card.all.click\&vd\_source=27a7dfe7f23984062616fef51dbba7fa)（_GAMES系列的课质量真不错哇，喜欢图形学游戏引擎的同学可以多看看，做做cw，网上有很多做完的作业，如果手搓完GAMES101的作业应该会对图形学有更深的理解，作者是懒狗，很后悔没写_），然后再来看这门课。如果只是想要学习一下OpenGL的同学，可以直接看看[LearnOpenGL](https://learnopengl-cn.github.io)

#### INT 201 Decision Computation and Language

Delivered by: Yushi Li&#x20;

Programming Language: 无&#x20;

Workload：★★☆☆☆ (2/5) 课程收获: ★★☆☆☆ (2/5)

讲得不咋滴，印象很深的是有一个TTL给的答案画生成树要先把CFL换成Chomsky范式，但是也没有人讲这个，还是和同学在讨论中发现的。也没有公布两个cw的评分细则，包括期末的回答题目的格式。[哈工大的形式语言与自动机](https://www.bilibili.com/video/BV1oE4116794/?spm\_id\_from=333.337.search-card.all.click)可以完美替代这门课的内容，只要看下每周TTL的答题格式就好了。不过个人认为如果因为格式扣分是真\*\*，别的方法就能算我错？油管上有一门MIT的类似课程讲得也很好,可以自行搜寻。
