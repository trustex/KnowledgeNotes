# Java并发编程

线程安全性

竞态条件

原子性

可见性

不可变对象:

 	1. 对象创建以后状态不能修改。
	2. 对象的所有域都是final类型。
	3. 对象是正确创建的(在对象创建期间，没有this逸出)

* 可变状态是至关重要的:所有的并发问题都可以归结为如何协调对并发状态的访问，可变状态越少，就越容易确保线程安全性。

* 尽量把域声明为final类型，除非需要他们是可变的。

  