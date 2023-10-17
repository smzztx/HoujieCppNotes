标准库中，有很多类重载了()，这就是仿函数。  
![](attachments/5.1.1function-like%20classes.jpg)
标准库中，仿函数为什么要继承奇特的 base classes，具体原因需要在STL课程查看。  
![](attachments/5.1.2function-like%20classes.jpg)
![](attachments/5.1.3function-like%20classes.jpg)
这个类所占的大小是多少？看占用实际是看数据占用的大小，理论是0，实际可能是1。  
![](attachments/5.1.4function-like%20classes.jpg)