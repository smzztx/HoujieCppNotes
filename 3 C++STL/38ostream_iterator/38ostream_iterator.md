重载了 operator*()，这里相当于 *result 不起任何作用，又重载了 operator，这里 `*result = *first;` 就相当于 `cout << *first; cout << ", ";`。
![](attachments/38.1.1ostream_iterator.jpg)