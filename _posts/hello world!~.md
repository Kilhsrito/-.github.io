## 今天算是写博客的第一天吧~！
### 由于最近工作比较忙，但是还是要养成每天写博客的习惯，即使每天只写一点点，但是还是要坚持下去！
### 那么今天就来讲一下
# 栈介绍 
基本栈介绍 

栈是一种典型的后进先出 (Last in First Out) 的数据结构，其操作主要有压栈 (push) 与出栈 (pop) 两种操作，如下图所示（维基百科）。两种操作都操作栈顶，当然，它也有栈底。、


![](https://ctf-wiki.org/pwn/linux/user-mode/stackoverflow/x86/figure/Data_stack.png)

高级语言在运行时都会被转换为汇编程序，在汇编程序运行过程中，充分利用了这一数据结构。每个程序在运行时都有虚拟地址空间，其中某一部分就是该程序对应的栈，用于保存函数调用信息和局部变量。此外，常见的操作也是压栈与出栈。需要注意的是，程序的栈是从进程地址空间的高地址向低地址增长的。
函数调用栈 
#明天再说！！