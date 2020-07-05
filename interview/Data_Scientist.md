# Interview for Data Scientist

## 项目篇:
### 遇到问题的改进思路和应对措施

## 知识篇:
### 1. 概率论--贝叶斯公式,全概率公式
#### 贝叶斯公式
贝叶斯的数学公式十分简单

    一， 你要有<b>先验概率P（A）</b>  

    二， <b>似然性 P（B|A）</b>  

    三,  最终得到<b>后验概率P（A|B）</b>。这三者构成贝叶斯统计的三要素。  

似然性实用条件概率表达， 后验也用条件概率来表达， 基于此的贝叶斯定律数学方程极为简单：

<p align="center"><p align="center"><p align="center">![image](https://github.com/whw199833/2021_for_work/blob/master/images/20dc6dd3b18760e89f6be2682c2df0ee_720w.jpg)</p>

贝叶斯分析的思路对于由证据的积累来推测一个事物发生的概率具有重大作用， 它告诉我们当我们要预测一个事物， 我们需要的是首先根据已有的经验和知识推断一个先验概率， 然后在新证据不断积累的情况下调整这个概率。整个通过积累证据来得到一个事件发生概率的过程我们称为贝叶斯分析。

<p align="center"><p align="center">![image](https://github.com/whw199833/2021_for_work/blob/master/images/b31aa378530e552127512be06a522b70.svg)</p>

#### 全概率公式
全概率就是表示达到某个目的，有多种方式（或者造成某种结果，有多种原因），问达到目的的概率是多少（造成这种结果的概率是多少）？

全概率公式：

    设事件L1 ~ Ln是一个完备事件组，则对于任意一个事件Ｃ，若有如下公式成立：
<p align="center">![image](https://raw.githubusercontent.com/whw199833/2021_for_work/master/images/20170718154223896.gif)</p>
    
## 工具篇:
### 1. SQL 子查询, 子表命名