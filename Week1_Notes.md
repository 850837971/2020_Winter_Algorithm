# Week1 学习总结
## 1. Stack
### 
1. Stack 先入后出(LIFO)，添加和时间复杂度都为O(1), 查询复杂度为O(n)
pop, push, empty, top
```C++
std::stack<unsigned> s;
// inserts element at the top
s.push(1);
s.push(24);
s.push(65);
// accesses the top element
std::cout << s.top() << endl;
// removes the top element
s.pop();
if (!s.empty()){
  s.pop();
  std::cout << s.top() << endl;
}
```

## 2.Queue
### 
1. Queue 先入先出(FIFO), 添加和时间复杂度都为O(1), 查询复杂度为O(n)
2. 常见的function
* empty
* size
* front 
* back 

## 3.Deque
### 
1. double-ended queue, 添加和时间复杂度都为O(1), 查询复杂度为O(n)

## 4.Priority Queue
###
1. 插入和删除复杂度为O(1), 取出操作为O(logN), 按照元素的优先级
示例代码：
```c++
priority_queue<int, vector<int>, greater<int>> q1;
```
## 70.爬楼梯
### 思路：化繁为简，从1开始，接着是2（找最近重复的子问题）因为只能for while， if, recursion






