set/multiset 元素的 value 和 key 合一：value 就是 key。
![](attachments/21.1.1set、multiset深度探索.jpg)
容器 set 底层是通过 rb_tree 实现的。
![](attachments/21.1.2set、multiset深度探索.jpg)
VC6 内部实现了 identity()。
![](attachments/21.1.3set、multiset深度探索.jpg)
用自己的 find() 比通用的 find() 效率高。
![](attachments/21.1.4set、multiset深度探索.jpg)