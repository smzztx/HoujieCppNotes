这里老师讲的比《Effective C++》条款47：请使用traits classes表现类型信息 好多了，视频和书都过一遍理解得更清楚。
![](attachments/15.1.1迭代器的设计原则和Iterator%20Traits的作用与设计.jpg)
![](attachments/15.1.2迭代器的设计原则和Iterator%20Traits的作用与设计.jpg)
如果只是迭代器，前面的设计也够用了，但是这里要能区分传统指针和迭代器，所以后面要用iterator_traits。
![](attachments/15.1.3迭代器的设计原则和Iterator%20Traits的作用与设计.jpg)
用到了模板的偏特化来区分传统指针和迭代器。
![](attachments/15.1.4迭代器的设计原则和Iterator%20Traits的作用与设计.jpg)
![](attachments/15.1.5迭代器的设计原则和Iterator%20Traits的作用与设计.jpg)
![](attachments/15.1.6迭代器的设计原则和Iterator%20Traits的作用与设计.jpg)
