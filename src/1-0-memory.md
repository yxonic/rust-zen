# 内存控制

程序员常常会问自己这样一个问题，如何提高我的程序的性能？有个有点偷懒但很有效的答案，就是寻找当前的**性能瓶颈**并优化它。更具体一点说，性能瓶颈一般在哪呢？第一有可能的瓶颈自然是算法，但第二可能便是内存控制了。

> 程序 = 算法 + 数据结构 （或者更简单的版本：**程序 = 过程 + 数据**）

*（以下为提纲）*

类似的程序员希望对内存有更精细的控制的场合还有很多。

长久以来的困境：现有的语言中控制和不易出错无法兼得。

控制和复杂性无法兼得很好理解。但复杂并不应该意味着容易出错。选择了更多控制，真正应当面对的是复杂性而不是出错可能。

很多语言采用的方案是绕开复杂性：控制力削弱，或造成假象。

真正的方案：直面和试图解决复杂性。

直面复杂性：be explicit，背后发生什么越清晰，复杂性越直接。本章节介绍。

解决复杂性：抽象，后续章节介绍。