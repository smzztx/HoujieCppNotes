对象模型：关于 this 。调用成员函数会隐式传入 this ，下图中虽然调用的是父类的成员函数，但是父类的成员函数中会调用子类的 Serialise() 成员函数。
![](attachments/18关于this.jpg)