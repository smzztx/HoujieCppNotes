这里用模板的泛化和特化来去掉 const 和 volatile 。
![](attachments/43.1.1type%20traits%20实现.jpg)
这里先去掉 const 和 volatile，接着又用模板的泛化和特化来判断是否是整型。
![](attachments/43.1.2type%20traits%20实现.jpg)
蓝色这些 _is_xxx 未曾出现于 C++ 标准库源代码，可能是从编译器获取的信息。
![](attachments/43.1.3type%20traits%20实现.jpg)
同样的这里蓝色的部分也没在 C++ 标准库源代码里找到。
![](attachments/43.1.4type%20traits%20实现.jpg)