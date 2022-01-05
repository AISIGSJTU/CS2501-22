
<head>
    <script src="https://cdn.mathjax.org/mathjax/latest/MathJax.js?config=TeX-AMS-MML_HTMLorMML" type="text/javascript"></script>
    <script type="text/x-mathjax-config">
        MathJax.Hub.Config({
            tex2jax: {
            skipTags: ['script', 'noscript', 'style', 'textarea', 'pre'],
            inlineMath: [['$','$']]
            }
        });
    </script>
</head>


# CS2501-21

2021年秋离散数学（CS2501）课程网站

* TOC {:toc}

## 考前复习

更新时间：2022/1/5 16:48

1. 仔细阅读昨晚习题课的内容，[第四次习题课](./exercises/习题课04.pdf)覆盖了数理逻辑部分的重要题型与集合论部分的题目解答。
2. 选择题部分注意解题技巧。可行的方法包括：
   - **真值表法**。对于过于复杂的命题，可以使用真值表直接得到命题的真假或者进行后续的主合取或者析取范式的初步结论。**真值表法不要在解答题中使用。**
   - **举反例法**。对于判断命题是否普遍有效、判断性质是否成立非常有用。参考数理逻辑例题4.8判断是否普遍有效，集合论9.5例题3判断集合性质是否成立。
   - **作图法**。对于集合运算和性质判断可以使用文氏图方法。
3. 解答题部分注意。
   - **不要留空白！**
   - 数理逻辑部分题目都是套路，注意习题课中标注的重点。**最重要的是细心，不要出现低级错误。**
   - 集合论部分的证明回归课本。例如课上的集合性质的证明使用的方法能否推广使用，书上的性质要灵活利用。

## 复习题纠错

更新时间：2022/1/4 20:58

- 1.1：可满足的命题公式，其否定还是可满足的，答案纠正为**C**。
- 2.9：主合取范式纠正为 $\wedge_{1;2}$，原来的答案符号错误。
- 4.8：答案纠正为**不是**。可以给出反例：$P(0)=Q(0)=Q(1)=0, P(1)=1$，$(\exist x)(P(x)\leftrightarrow Q(x)) = T, (\exist x)P(x) \rightarrow (\exist x)Q(x) = F$，原式结果为 $F$，不是普遍有效。
- 5.1：答案纠正为**D**。具体参考教材75页。前束范式对前束量词没有次序要求。前束范式也是不唯一的。
- 5.2：答案纠正为**C**。
- 5.12：在化简前束范式时，第二行最后否定词内移出现错误，因此后面的解答也不正确。

![](https://raw.githubusercontent.com/ZinuoCai/Image-Bed/image-bed/2021/%E6%89%AB%E6%8F%8F%E5%85%A8%E8%83%BD%E7%8E%8B%202022-01-04%2021.38n_1.jpg)

## 课程通知 / News

- **第四次习题课PPT已经上传，[视频](https://jbox.sjtu.edu.cn/l/M10ZMV)**

- **[集合论参考答案](./exercises/复习题2参考答案.pdf)** 更新时间 2022/1/4 15:38

- **[数理逻辑参考答案](./exercises/复习题1参考答案.pdf)** 更新时间 2022/1/4 12:31

- **[2021年秋离散数学复习题集合论](./exercises/2021年秋离散数学复习题2.pdf)**

- **[2021年秋离散数学复习题数理逻辑](./exercises/2021年秋离散数学复习题1.pdf)**

- 2021/12/30：第十六周课后作业已经发布，截止时间为 202/1/2 23:59

- 2021/12/21：第十五周课后作业已经发布，截止时间为 2021/12/26 23:59

- 2021/12/12：第十三周课后作业已经发布，截止时间为 2021/12/19 23:59

- 2021/11/22：第十一周课后作业已经发布，截止时间为 2021/11/28 23:59

- 2021/11/15：第十周课后作业已经发布，截止时间为 2021/11/21 23:59

- 2021/11/5：逻辑第四章预习题已经发布，截止时间为 2021/11/8 16:00

- 2021/11/5：第二次习题课补充题已经发布，习题课时间为 2021/11/8。习题课的主要内容包括
  - 图论测试
  - 数理逻辑第一、二章预习题与课后题
  - 补充题

- 2021/11/4：图论考试分数将于2021/11/5上传，有疑问请于当日16:00-18:00至电院群楼3号楼东309查询成绩

- 2021/11/4：第八周课后作业已经发布，截止时间为 2021/11/14 23:59

- 2021/10/25：第七周课后作业已经发布，截止时间为 2021/10/31 23:59

- 2021/10/11：图论考试在第六周周四 2021/10/21，时长1.5小时

- 2021/10/19：补充题答案已经上传，在习题课ppt中也有

- 2021/10/11：第五周课后作业已经发布，截止时间为 2021/10/17 23:59

- 2021/10/5：第一次习题课补充题已经发布，习题课时间为 2021/10/9

- 2021/9/29：第三次预习题已经发布，截止时间为 2021/10/8 23:59

- 2021/9/28：第三周课后作业已经发布，截止时间为 2021/10/7 23:59

- 2021/9/23：第二次预习题已经发布，截止时间为 2021/9/27 16:00

- 2021/9/18：第一周课后作业已经发布，截止时间为 2021/9/21 23:59

- 2021/9/13：第一次预习题已经发布，截止时间为 2021/9/17 23:59

- 2021/9/13：欢迎开始**离散数学（CS2501）**的学习！

## 课程材料 / Material

| 章节            | 课件                                                      |
| --------------- | --------------------------------------------------------- |
| 作业提交要求    | [作业提交要求](others/作业提交要求.pdf)                   |
| 图论 第一章     | [图论-Chapter01.pdf](./slides/图论-Chapter01.pdf)         |
| 图论 第二章     | [图论-Chapter02.pdf](./slides/图论-Chapter02.pdf)         |
| 图论 第三章     | [图论-Chapter03.pdf](./slides/图论-Chapter03.pdf)         |
| 数理逻辑 第一章 | [数理逻辑-Chapter01.pdf](./slides/数理逻辑-Chapter01.pdf) |
| 数理逻辑 第二章 | [数理逻辑-Chapter02.pdf](./slides/数理逻辑-Chapter02.pdf) |
| 数理逻辑 第四章 | [数理逻辑-Chapter04.pdf](./slides/数理逻辑-Chapter04.pdf) |
| 数理逻辑 第五章 | [数理逻辑-Chapter05.pdf](./slides/数理逻辑-Chapter05.pdf) |
| 集合论 第九章 | [集合论-Chapter09.pdf](./slides/集合论-Chapter09.pdf) |
| 集合论 第十章 | [集合论-Chapter10.pdf](./slides/集合论-Chapter10.pdf) |
| 集合论 第十一章 | [集合论-Chapter11.pdf](./slides/集合论-Chapter11.pdf) |

## 课后作业 / Exercise

| 时间   | 作业 |
| ------ | ---- |
| 第一周 | 图论 P9: 1，2，3，7，8（邻接矩阵、关联矩阵）     |
| 第三周 | 图论 P35: 1，2，3，6，8，9，10              |
| 第五周 | 图论 P66: 1，2，14，16 |
| 第七周 | 数理逻辑 P12：1(2,4,6,8)，4(2,4,6)，5(2,4,6,8)，6(2) |
| 第八周 | 数理逻辑 P37：1(1, 3)，2，3，4(2)，5(8)，7(10,11)，8(4,5,6,及补充)，9(1)，12(1) |
| 第十周 | 数理逻辑 P66：1(1,2,4,6,8,9)（若不是合式公式，说明原因），2(3) ，3(2,3) ，4(2)，5(2,4,6,8,10)，7(10) ，8(2,4,6,7)，10(1,3,5,7) |
| 第十一周 | 数理逻辑 P84：1(1,3,5,7,9)，2(2,4,6,8)，3(7,8,9,10,11,12)，4(1,2,3,4,5,9,10)，5(1,2,3,4)|
| 第十三周 | 数理逻辑 P156：1(4)，2(3)，5(偶数)，6(3)，7(1,5)，8(3)，11(4)，12(4)，15(1)，16(1)，17(6) |
| 第十五周 | 数理逻辑 P158：18(4)，21，22，27；P189：12(2)，16，17(2)，18(4)，22，27 |

## 习题课 / 随堂测试 / Exam

### 习题课

| 时间      | 补充题                                                    | 习题课 |
| --------- | --------------------------------------------------------- | ------ |
| 2021/10/9 | [补充题](./exercises/习题课01-补充题.pdf)<br>[参考答案](./exercises/习题课01-补充题答案.pdf) |[第一次习题课](./exercises/习题课01.pdf)|
| 2021/11/5 | [补充题](./exercises/习题课02-补充题.pdf)<br>[参考答案](./exercises/习题课02-补充题答案.pdf) | [第二次习题课](./exercises/习题课02.pdf) |
| 2021/12/21 |  | [第三次习题课](./exercises/习题课03.pdf) |
| 2022/1/4 |  | [第四次习题课](./exercises/习题课04.pdf) |

### 随堂测试

- [2020 年秋《离散数学》图论测试](exams/2020年秋《离散数学》图论测试.pdf)

- [2020年秋《离散数学》图论测试参考答案](exams/2020年秋《离散数学》图论测试参考答案.pdf)

- [2021 年秋《离散数学》图论测试](exams/2021年秋《离散数学》图论测试.pdf)

- [2021年秋《离散数学》图论测试参考答案](exams/2021年秋《离散数学》图论测试参考答案.pdf)

