## 1.moveable 元素对容器效能的影响
![](attachments/45.1.1movable元素对于deque速度效能的影响.jpg)
![](attachments/45.1.2movable元素对于deque速度效能的影响.jpg)
![](attachments/45.1.3movable元素对于deque速度效能的影响.jpg)
![](attachments/45.1.4movable元素对于deque速度效能的影响.jpg)
![](attachments/45.1.5movable元素对于deque速度效能的影响.jpg)
  
## 2.写一个 moveable class
move ctor 和 move assignment 赋值结束后需要将原值赋为 NULL，析构函数也需要先判断是不是 NULL 然后再 delete。
![](attachments/45.2.1movable元素对于deque速度效能的影响.jpg)
![](attachments/45.2.2movable元素对于deque速度效能的影响.jpg)