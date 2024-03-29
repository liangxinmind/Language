# 实验五 数组与字符串

## 一．实验目的

1.  熟练掌握数组的使用方法

2.  掌握数据排序的算法

3.  掌握数组联合循环结构的编程思想

4.  掌握使用字符串处理问题的方法

5.  掌握简单的程序调试方法

## 二．知识要点

1.  理解一维和二维数组的定义和使用

2.  理解数据排序的基本算法

3.  掌握字符串的基本处理方法

4.  训练把应用问题转换为程序算法的思维能力

## 三. 实验内容

1. 成绩分析系统。用户输入10个学生的成绩(0-100)，请输出90分以上学生的百分比和低于平均分的学生的百分比。

2. 歌唱比赛打分系统（用一个程序完成）。

- 十个评委输入分数（80-100），当某位评委输入的分数不合理时，提示该编号评委重新输入。
如：输入80 90 85 85 80 90 95 96 97 99

- 十个合理分数输入后，利用冒泡法将10个分数从大到小排序输出。
如：输出99 97 96 95 90 90 85 85 80 80

- 增加了第11位评委打分，打分后将该分数插入到b中已排序的分数中，从大到小输出11个分数。增加94分， 则输出
99 97 96 95 94 90 90 85 85 80 80

- 计算11个评委的平均分并输出。

3. 输出Fibonacci数列的前20个数据，如：1 2 3 5 8...

4. 输入8个整数，请找到其中所有出现超过一次的数字。
如：用户输入 7 5 4 3 2 1 2 4
则输出： 4 2

5. 简单数独。一个3行3列的二维数组当满足下列条件时表明它能构成一个简单数独：每一行、每一列内的数字均含1,2,3。请根据用户输入的一个3行3列的二维数组，编程给出是否为正确的简单数独。

6. 实现矩阵（3行3列）的转置（即行列互换）

7. 任意输入两个字符串，将它们连接成一个字符串（不使用strcat函数）。

8.  输入一字符串，内有若干个字符，要求程序将字符串中所有非数字和字母删除后输出。

9.  输入一行字符，单词之间用空格隔开，统计其中有多少个单词。

10. 某天你到超市买了4双筷子，每双筷子的长度不尽相同，你把全部筷子都放在购物袋里面高高兴兴拿回家，路上不小心掉了一根。请用程序找出你漏掉的筷子是多长的。
例如,输入的剩余的7根筷子的长度为：1, 2, 3, 2, 1, 3, 2
则输出：漏掉的筷子的长度为2
(当输入的筷子数据异常时输出：找不到漏掉的筷子)

**四. 实验要求**

1.  注意数组长度和下标越界问题。

2.  注意数组与循环的配套使用。.

3.  注意字符与字符串的区别。

4.  会通过设置断点, 单步运行, 观察数组中各变量的方式,
    或手动代入跟踪代码流程的方式, 解决程序中存在的问题。
