## `Obj-c`对象、类的本质是通过什么数据结构实现的？

结构体。

譬如一个最常见的 `Nsobject` 对象。将其编译为 `C++` 代码后，实际上就是一个 `Nsobject_Impl` 结构体。