# DesignPatterns_work2
This is my DesignPatterns_work2.

==比较的是2个对象的地址，而equals比较的是2个对象的内容。

clone方法执行的是浅拷贝。
如果想要深拷贝一个对象， 这个对象必须要实现Cloneable接口，实现clone方法，并且在clone方法内部，把该对象引用的其他对象也要clone一份,这就要求这个被引用的对象必须也要实现Cloneable接口并且实现clone方法。
