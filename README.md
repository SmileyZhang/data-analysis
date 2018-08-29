# 项目目的
我个人关于数据分析的资料整理和心得体会总结，方便自己查阅、学习和使用。

# 联系作者
邮箱：SmileyZhang@qq.com

# 资料篇
## 关于github
### [《Github漫游指南》](https://github.com/phodal/github)
作者详细介绍了自己使用`github`的多年经历和心得，其中也涉及到他做程序开发过程中的一些思考。据文章说，他是大陆contribute数最多的人。

## 关于机器学习
### 《sklearn与tensorflow机器学习实用指南 hands-on ml with sklearn and tensorlow》
英文影印版，购自京东。用到python数据分析的很多常用库，如numpy、matplotlib、sklearn和tensorflow，里面涉及大量监督和无监督机器学习模型，个人感觉比《机器学习实战》更适合作为机器学习的入门书，框架更为清楚。

#### [作者的github](https://github.com/ageron/handson-ml)
里面有原书各章节略过的代码实现部分和对原书的一些补充，还有各章节习题答案的上机部分。

#### [作者放在jupyter上的原书补充和课后练习答案](http://nbviewer.jupyter.org/github/ageron/handson-ml/tree/master/)
内容跟作者放在github上的大致一样，但是作者说github的jupyter viewer比这个慢，我打开试了一下，确实是这个更快一点。

#### [非官方中文翻译的github](https://github.com/apachecn/hands_on_Ml_with_Sklearn_and_TF)
国内自发组织的对原书的翻译（目前还没出官方中文书），对于原书有些文字描述比较多的部分，看这个比看英文快，查阅速度也比原书快，毕竟母语……翻译质量不算特别好，有些错误甚至让人感觉译者自己都不懂作者在说什么，强行逐词翻译硬搬过来的，然后大多缩略词只给出了缩略词和翻译后的全称，没有注明原本的英文全称，导致有些内容比较费解。

#### 本书里出现的其他资料
[tensorflow的一个model zoo](https://github.com/tensorflow/models)

[一个caffe model zoo的转换器](https://github.com/ethereon/caffe-tensorflow)

### 《机器学习实战 machine learning in action》
中文kindle版，购自亚马逊。上来就晾一堆代码给我，不大能看得下去，可读性不如《实用指南》，暂时搁置，等到对机器学习比较熟悉以后再回过来看看，也许到时能好一些。

#### [github上一个关于这本书和机器学习的总结](https://github.com/apachecn/AiLearning)
看目录感觉很厉害的样子，里面给出了关于机器学习的课程等资料，等看完《实用指南》可以了解一下。

### 《python数据分析 Python for Data Analysis》
本书作者是pandas库的作者，7月刚出了[第二版的正式中文版](https://item.jd.com/12398725.html)（比[第二版的英文影印版](https://item.jd.com/12310353.html?dist=jd)贵个十几块钱），关注一下京东最近的活动，等看完《实用指南》再说吧。

### Siraj Raval的视频和配套资料
#### [6周学会深度学习](https://github.com/llSourcell/Learn_Deep_Learning_in_6_Weeks)
#### [100天机器学习之旅](https://github.com/llSourcell/Machine_Learning_Journey)
最初看到这两个教程是在b站关注的`景略集智`发出的视频，原视频来自`youtube`上分享机器学习相关内容的视频制作者`Siraj Raval`。只粗略看了一下两个教程的readme文档，印象还不错，下回仔细研究。

# 心得篇
[资料篇](#资料篇)为看过或将要看的资料梳理，心得篇的内容则完全是自己原创。
## markdown语法
在github和jupyter notebook上都用到markdown语法，为了方便，需要记录一些常用语法备忘，所以写了这篇[《我的Markdown笔记》](https://github.com/SmileyZhang/data-analysis/blob/master/my-notes-of-markdown.md)。这是我个人总结的markdonw常用语法，对比网上的官方文档或者其他资料，自己写的文章总是更符合自己习惯些。

从8月20日开始，印象笔记mac beta版开始支持markdown，还可以分屏预览（左边显示源码，右边显示预览），更直观地看到更改源码以后的效果，开心！

# idea篇
有时候会冒出一些想法暂时来不及实现，但如果不及时记录下来，过段时间可能就忘了，等到下次需要用的时候，只能懊悔自己上次想到这个问题怎么没解决。因此设置这个版块让自己及时记录想法和未来安排，一个一个去解决就好了。
## 自动生成具有导航功能的md目录
每次写完md文档，手动去写目录都觉得特别麻烦，容易出错不说，一旦文章发生了修改，人工对照修改前后该目录真是让人难受。网上有一些第三方软件可以生成目录，但是我不太喜欢给自己电脑装没有靠谱官方作保的软件，所以有时间自己去编一个吧。
## 写简历
附上github和博客。
## 深入了解下列领域
并发、多线程、分布式。
