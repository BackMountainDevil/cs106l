# CS106L

[CS106L 课程网站](http://web.stanford.edu/class/cs106l/)

2024.09 有 7 个 assginment

# assign

代码存到 [github]() or [gitee](https://gitee.com/anidea/cs106l-assignments/tree/create/)，出于课程诚信考虑，课程结束前不会公开

[1 SimpleEnroll](assign/1.md)

# Original 106L Course Reader

[Course Reader](http://web.stanford.edu/class/cs106l/full_course_reader.pdf)

### Introduction

举例子求数列均值的代码（循环累加同除），升级版用 accumulate 除 distance，并说后者更加安全、简洁、通用

```c++
double GetAverage(double arr[], int numElems) {
double total = 0.0;
for(int h = 0; h < numElems; ++h)
total += arr[h] / numElems;
return total;
}
```

课程假设读者的c++水平等同于学过CS106B/X课程

带答案的练习用菱形（♦）标记

最后说该课程不是C++参考书。参考书推荐了 Bjarne Stroustrup的《C++编程语言》第三版、Lippman、Lajoie和Moo合著的《C++ Primer》第四版。也推荐了一些在线资源：
- [C++ FAQ](http://www.parashift.com/c++-faq-lite/)
- [cplusplus 标准库讨论](https://cplusplus.com/)

### Chapter 0: What is C++?

# 相关阅读

https://csdiy.wiki/%E7%BC%96%E7%A8%8B%E5%85%A5%E9%97%A8/cpp/CS106L/

[CS106L 过程记录 OleehyO 2024-02-21](https://zhuanlan.zhihu.com/p/683265937)：补充了一些工具

[CS106L系列 序言 砸楼梯](https://zhuanlan.zhihu.com/p/555321969)