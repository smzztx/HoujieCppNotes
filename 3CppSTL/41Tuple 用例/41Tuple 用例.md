C++11 标准新引入了一种类模板，命名为 tuple（中文可直译为元组）。tuple 最大的特点是：实例化的对象可以存储任意数量、任意类型的数据。它支持使用 std::get 、std::get_if 和 std::ignore 来访问元组中的元素，也支持使用 std::make_tuple 和 std::tie 来构造和分解元组。
![](attachments/41.1.1Tuple%20用例.jpg)
tuple 是使用递归继承来实现的，具体可以仔细看下图。
![](attachments/41.1.2Tuple%20用例.jpg)