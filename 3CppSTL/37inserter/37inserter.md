copy() 会把之前的覆盖，如果想把赋值改插入，可以用迭代器适配器 inserter ，这里比较巧妙的是在不改变 copy() 的情况下，重载了 operator= ，变成调用 insert()。
![](attachments/37.1.1inserter.jpg)