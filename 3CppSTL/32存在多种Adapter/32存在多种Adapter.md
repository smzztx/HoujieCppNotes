Adapters 并不是独立的一块，作用于迭代器的就是迭代器适配器，作用于容器的就是容器适配器，作用于仿函数的就是仿函数适配器。
![](attachments/32.1.1存在多种Adapter.jpg)
容器适配器：stack、queue，这两个都缩小了 deque 的范围，而且还有成员函数名字的更改。
![](attachments/32.1.2存在多种Adapter.jpg)