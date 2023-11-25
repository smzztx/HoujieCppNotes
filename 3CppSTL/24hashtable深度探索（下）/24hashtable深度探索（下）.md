![](attachments/24.1.1hashtable深度探索（下）.jpg)
数字类型的 hash 直接返回数字。
![](attachments/24.1.2hashtable深度探索（下）.jpg)
C 风格的字符串这里提供了一种计算 hash 值的方式，也可以自己定义，就是使得元素经 hash code 映射之后能够“够杂够乱够随机”地被置于 hashtable 内。愈是杂乱，愈不容易发生碰撞。
![](attachments/24.1.3hashtable深度探索（下）.jpg)
最终都是调用 hash(key)%n 。
![](attachments/24.1.4hashtable深度探索（下）.jpg)