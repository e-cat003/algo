# 什么是时间和空间复杂度

# 时间复杂度
> 首先要说的是，时间复杂度的计算并不是计算程序具体运行的时间，而是算法执行语句的次数。
> <br/> 当我们面前有多个算法时，我们可以通过计算时间复杂度，判断出哪一个算法在具体执行时花费时间最多和最少。

### 时间复杂度有哪些
- 常见的时间复杂度有：
- 常数阶O(1),
- 对数阶O(log2 n),
- 线性阶O(n),
- 线性对数阶O(n log2 n),
- 平方阶O(n^2)，
- 立方阶O(n^3)
- k次方阶O(n^K),
- 指数阶O(2^n)。
- 随着n的不断增大，时间复杂度不断增大，算法花费时间越多。

### 计算方法
- ①选取相对增长最高的项
- ②最高项系数是都化为1
- ③若是常数的话用O（1）表示
- 如f（n）=2*n3+2n+100则O（n）=n3。

# 空间复杂度
> 空间复杂度是对一个算法在运行过程中临时占用存储空间大小的度量。

### 计算方法：
- ①忽略常数，用O(1)表示
- ②递归算法的空间复杂度=递归深度N*每次递归所要的辅助空间
- ③对于单线程来说，递归有运行时堆栈，求的是递归最深的那一次压栈所耗费的空间的个数，因为递归最深的那一次所耗费的空间足以容纳它所有递归过程。
