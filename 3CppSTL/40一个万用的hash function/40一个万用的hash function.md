## 1.引出问题
![](attachments/40.1.1一个万用的hash%20function.jpg)
![](attachments/40.1.2一个万用的hash%20function.jpg)
要实现自己类的 hash function 有两种方式，一种是写个自己类的 hash 运算类，并重载 operator()函数，第二种是写个自己的函数来运算。
![](attachments/40.1.3一个万用的hash%20function.jpg)
  
## 2.写自己的 Hash Function
这里有使用 TR1 中实现的一个万用 Hash Function，直接拿过来用的。这里有用到可变参数模板，实现递归调用。
![](attachments/40.2.1一个万用的hash%20function.jpg)
![](attachments/40.2.2一个万用的hash%20function.jpg)
![](attachments/40.2.3一个万用的hash%20function.jpg)
![](attachments/40.2.4一个万用的hash%20function.jpg)
  
## 3.实现 hash 函数的偏特化
![](attachments/40.3.1一个万用的hash%20function.jpg)
GNU4.9 版本是有 string 版本的 hash 偏特化。
要实现 hash 函数的偏特化，必须放在 std 内。
![](attachments/40.3.2一个万用的hash%20function.jpg)
