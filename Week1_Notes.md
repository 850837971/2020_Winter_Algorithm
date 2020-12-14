# Week1 学习总结
## 1. Stack
### 
1. Stack 先入后出(LIFO)，添加和删除的时间复杂度都为O(1)
2. 常见function
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
1. Queue 先入先出(FIFO), 添加和时间复杂度都为O(1)
2. 常见的function
* empty
* size
* front 
* back 





