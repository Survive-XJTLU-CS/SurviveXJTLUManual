#前言
我校ics的课程涵盖还是比较标准的，基本的计算机核心课都有了，申请研究生肯定是足够的。但是如果是希望自己能够从事一些开发工作或者是科研访学，这些课程是远远不够的，可以说如果仅仅学课内课程的话什么活也干不了（非常抽象），更别说有些课的质量实在是一言难尽。这篇会分享ics基本的核心课信息+一点网课推荐。作者是20届的，所以是根据20届的课设和lecturer写的，后续有可能会做出调整，但大体不会改变。

## Y1-S2
大一下学期学校应该会分配两门水课**CPT001 Professional Skills in Computer Science**和**CPT002 Current Trends and Emerging Topics in Computer Science**，我记得一门课会要求写SoP和CV，一门是写应用技术到实际的论文，给分很抽象，也没什么实际应用价值。（作者这俩门得分都一般，之前没有接触过cs，有一位有cs基础的朋友论文写的是KNN应用到救火什么的，虽然我感觉也是扯犊子，但涉及到一点AI算法了，分拿的老高了TnT）

上这两课没什么意思，几乎等于浪费时间。如果是大一的新同学选了ics，一点foundation都没有推荐有空看一下 [MIT-Missing-Semester](https://missing.csail.mit.edu/2020/) **例如 Shell 编程、命令行配置、Git、Vim、tmux、ssh** 这些对于一个programmar很重要的知识，但是学校没有教的，这门课都会涉及到。（很多求职jd里面都会要求shell脚本编程）起码不至于连编译器都不会装。（作者见过很多这样的同学）

---
## Y2-S1 
### CPT 101 Computer Systems

### CPT 103 Introduction to Databases

### CPT 107 Discrete Mathematics and Statistics

### CPT 111 Java Programming

---

## Y2-S2 
### CPT 102 Data Structures

### CPT 103 Operating Systems Concepts

### CPT 102 Algorithmic Foundations and Problem Solving

### INT 104 Artificial Intelligence

---

## Y3-S1 
### CAN201 Introduction to Networking
Delivered by Dr. Fei Chen and Dr. Wenjun Fan

这门课在20届之前应该都是Fei Chen一个人带的，19届的cw据说很难，给了一个diy的protocol然后手搓C/S，我校为数不多的还可以的coding exercise，评分标准是按传输文件的速度，完全符合正态分布，被卷成麻花，report基本不看，后来据说惨遭投诉课程难度下降(cw难度被腰斩了)。分数结构上cw的占比很高(40%)，和期末(45%)差不多。有百分之15是lab课白送的，基本只要上了lab就能拿满。学期初还说要考勤，搞得人心惶惶的，结果每节课都有录播，不用去lab，看完录播课提交每周的assignment就可以拿满15分。在期中之前的lecture是Fei Chen讲的，后半学期则是Wenjun Fan。 课程结构直接是照抄的[Computer Networking: A Top-Down Approach](https://gaia.cs.umass.edu/kurose_ross/index.php)。非常经典的计算机网络课程，进度非常快，讲课进度和umass官方提供的视频课程差不多，个人感觉跟着这个进度是吃不透这门课的。如果想找替代课程的同学，推荐观看[中科大计算机网络](https://www.bilibili.com/video/BV1JV411t7ow/)。课程时长比较恐怖，2小时只讲我校一半lecture的东西，不做多赘述，自行观看。
有关cw：20届的cw变成了groupwork，并且分为了两个part，每个part判分分为code和report两个部分。Pt.1是阉割版本的19cw，给定了protocol和server文件，只要求完成对应的client文件，难度急剧下降。Pt.2是实现一根根据OpenFlow protocol的SDN重定向流量，还是比较有意思的，虽然实现功能只要在OPF1.3的基础上多加几行代码，但是要看懂SDN控制器的工作流程需要花一点时间，作者猛看OPF文档才找到了对应的API，最抽象的是下一节lab直接把答案需要使用的API讲出来了。由于难度被阉割，所以每一组的判分不会很悬殊，甚至变成了report美工大赛。

### CPT 203

这门课可能会让很多同学失望的一门课，非常非常非常traditional的SE课程，PPT都快包浆了，课程也很无聊，作者只上了第一节lecture就再也没有去过了。同许多老旧软件工程课一样强调各种类图、文档设计、测试，大部分都是概念类的知识，猛猛背书就完事了。唯二涉及到一定代码的可能是高内聚低耦合部分会讲一点java代码的类设计还有是junit test。重中之中是时序图，类图，活动图，类图等图的设计和绘画，建议自己多使用visual paradigm等软件或者手画一下，期末时候占比很重。（奶奶的，这门课什么时候才能改革？？？？？？？？？？？？？？）

### CPT 102 Algorithmic Foundations and Problem Solving

### INT 104 Artificial Intelligence
