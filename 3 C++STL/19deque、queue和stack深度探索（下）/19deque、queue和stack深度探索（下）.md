## 1.容器 deque 如何模拟连续空间
![](attachments/19.1.1deque、queue和stack深度探索（下）.jpg)
这里讲的很清楚。
![](attachments/19.1.2deque、queue和stack深度探索（下）.jpg)
后++ 都是用前++ 来实现的；同样的 -- 也是一样。node 存放在连续区域内（vector）可以直接加或减来跳转缓冲区。
![](attachments/19.1.3deque、queue和stack深度探索（下）.jpg)
+= 需要先判断是否在同一缓冲区内。
![](attachments/19.1.4deque、queue和stack深度探索（下）.jpg)
![](attachments/19.1.5deque、queue和stack深度探索（下）.jpg)
  
## 2.容器 deque G4.9实现
G4.9实现的容器都是类似的。
![](attachments/19.2.1deque、queue和stack深度探索（下）.jpg)
![](attachments/19.2.2deque、queue和stack深度探索（下）.jpg)
  
## 3.容器 queue
![](attachments/19.3.1deque、queue和stack深度探索（下）.jpg)
  
## 4.容器 stack
stack，栈，先进后出。
![](attachments/19.4.1deque、queue和stack深度探索（下）.jpg)
  
## 5.除了 deque 还有哪些容器可以作为底层容器
![](attachments/19.5.1deque、queue和stack深度探索（下）.jpg)
![](attachments/19.5.2deque、queue和stack深度探索（下）.jpg)
![](attachments/19.5.3deque、queue和stack深度探索（下）.jpg)
  