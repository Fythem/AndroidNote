![公众号:玩转安卓Dev](https://gitee.com/zhpanvip/images/raw/master/project/group/wechat_dyh.png)



## Java基础

### Java面向对象与基础知识

- [Java中“==” 和 equals 有什么](https://github.com/zhpanvip/AndroidNote/wiki/%E9%9D%A2%E5%90%91%E5%AF%B9%E8%B1%A1%E4%B8%8EJava%E5%9F%BA%E7%A1%80%E7%9F%A5%E8%AF%86#1java%E4%B8%AD-%E5%92%8C-equals-%E6%9C%89%E4%BB%80%E4%B9%88)
- [为什么重写 equals 方法必须重写 hashcode 方法](https://github.com/zhpanvip/AndroidNote/wiki/%E9%9D%A2%E5%90%91%E5%AF%B9%E8%B1%A1%E4%B8%8EJava%E5%9F%BA%E7%A1%80%E7%9F%A5%E8%AF%86#2%E4%B8%BA%E4%BB%80%E4%B9%88%E9%87%8D%E5%86%99-equals-%E6%96%B9%E6%B3%95%E5%BF%85%E9%A1%BB%E9%87%8D%E5%86%99-hashcode-%E6%96%B9%E6%B3%95)
- [下面的代码在JVM中生成了几个String对象？JVM是如何对其进行内存分配的？](https://github.com/zhpanvip/AndroidNote/wiki/%E9%9D%A2%E5%90%91%E5%AF%B9%E8%B1%A1%E4%B8%8EJava%E5%9F%BA%E7%A1%80%E7%9F%A5%E8%AF%86#3%E4%B8%8B%E9%9D%A2%E7%9A%84%E4%BB%A3%E7%A0%81%E5%9C%A8jvm%E4%B8%AD%E7%94%9F%E6%88%90%E4%BA%86%E5%87%A0%E4%B8%AAstring%E5%AF%B9%E8%B1%A1jvm%E6%98%AF%E5%A6%82%E4%BD%95%E5%AF%B9%E5%85%B6%E8%BF%9B%E8%A1%8C%E5%86%85%E5%AD%98%E5%88%86%E9%85%8D%E7%9A%84)
- [了解String的intern()方法吗？它有什么作用？](https://github.com/zhpanvip/AndroidNote/wiki/%E9%9D%A2%E5%90%91%E5%AF%B9%E8%B1%A1%E4%B8%8EJava%E5%9F%BA%E7%A1%80%E7%9F%A5%E8%AF%86#4%E4%BA%86%E8%A7%A3string%E7%9A%84intern%E6%96%B9%E6%B3%95%E5%90%97%E5%AE%83%E6%9C%89%E4%BB%80%E4%B9%88%E4%BD%9C%E7%94%A8)
- [String、StringBuffer与StringBuilder有区别？](https://github.com/zhpanvip/AndroidNote/wiki/%E9%9D%A2%E5%90%91%E5%AF%B9%E8%B1%A1%E4%B8%8EJava%E5%9F%BA%E7%A1%80%E7%9F%A5%E8%AF%86#5stringstringbuffer%E4%B8%8Estringbuilder%E6%9C%89%E5%8C%BA%E5%88%AB)
- [访问修饰符public,private,protected,以及不写（默认）时的区别？](https://github.com/zhpanvip/AndroidNote/wiki/%E9%9D%A2%E5%90%91%E5%AF%B9%E8%B1%A1%E4%B8%8EJava%E5%9F%BA%E7%A1%80%E7%9F%A5%E8%AF%86#6%E8%AE%BF%E9%97%AE%E4%BF%AE%E9%A5%B0%E7%AC%A6publicprivateprotected%E4%BB%A5%E5%8F%8A%E4%B8%8D%E5%86%99%E9%BB%98%E8%AE%A4%E6%97%B6%E7%9A%84%E5%8C%BA%E5%88%AB)
- [final有哪几种用法？每种用法是什么含义？](https://github.com/zhpanvip/AndroidNote/wiki/%E9%9D%A2%E5%90%91%E5%AF%B9%E8%B1%A1%E4%B8%8EJava%E5%9F%BA%E7%A1%80%E7%9F%A5%E8%AF%86#7final%E6%9C%89%E5%93%AA%E5%87%A0%E7%A7%8D%E7%94%A8%E6%B3%95%E6%AF%8F%E7%A7%8D%E7%94%A8%E6%B3%95%E6%98%AF%E4%BB%80%E4%B9%88%E5%90%AB%E4%B9%89)
- [static 关键的作用](https://github.com/zhpanvip/AndroidNote/wiki/%E9%9D%A2%E5%90%91%E5%AF%B9%E8%B1%A1%E4%B8%8EJava%E5%9F%BA%E7%A1%80%E7%9F%A5%E8%AF%86#8static-%E5%85%B3%E9%94%AE%E7%9A%84%E4%BD%9C%E7%94%A8)
- [内部类可以引用外部类的成员吗？有没有什么限制？](https://github.com/zhpanvip/AndroidNote/wiki/%E9%9D%A2%E5%90%91%E5%AF%B9%E8%B1%A1%E4%B8%8EJava%E5%9F%BA%E7%A1%80%E7%9F%A5%E8%AF%86#9%E5%86%85%E9%83%A8%E7%B1%BB%E5%8F%AF%E4%BB%A5%E5%BC%95%E7%94%A8%E5%A4%96%E9%83%A8%E7%B1%BB%E7%9A%84%E6%88%90%E5%91%98%E5%90%97%E6%9C%89%E6%B2%A1%E6%9C%89%E4%BB%80%E4%B9%88%E9%99%90%E5%88%B6)
- [int和Integer有什么区别？](https://github.com/zhpanvip/AndroidNote/wiki/%E9%9D%A2%E5%90%91%E5%AF%B9%E8%B1%A1%E4%B8%8EJava%E5%9F%BA%E7%A1%80%E7%9F%A5%E8%AF%86#10int%E5%92%8Cinteger%E6%9C%89%E4%BB%80%E4%B9%88%E5%8C%BA%E5%88%AB)
- [Java 面向对象的特征有哪些方面？](https://github.com/zhpanvip/AndroidNote/wiki/%E9%9D%A2%E5%90%91%E5%AF%B9%E8%B1%A1%E4%B8%8EJava%E5%9F%BA%E7%A1%80%E7%9F%A5%E8%AF%86#11java-%E9%9D%A2%E5%90%91%E5%AF%B9%E8%B1%A1%E7%9A%84%E7%89%B9%E5%BE%81%E6%9C%89%E5%93%AA%E4%BA%9B%E6%96%B9%E9%9D%A2)
- [简述Java反射机制，反射的作用和应用？](https://github.com/zhpanvip/AndroidNote/wiki/%E9%9D%A2%E5%90%91%E5%AF%B9%E8%B1%A1%E4%B8%8EJava%E5%9F%BA%E7%A1%80%E7%9F%A5%E8%AF%86#12%E7%AE%80%E8%BF%B0java%E5%8F%8D%E5%B0%84%E6%9C%BA%E5%88%B6%E5%8F%8D%E5%B0%84%E7%9A%84%E4%BD%9C%E7%94%A8%E5%92%8C%E5%BA%94%E7%94%A8)
- [Java泛型是什么？泛型的类型擦除是怎么回事？](https://github.com/zhpanvip/AndroidNote/wiki/%E9%9D%A2%E5%90%91%E5%AF%B9%E8%B1%A1%E4%B8%8EJava%E5%9F%BA%E7%A1%80%E7%9F%A5%E8%AF%86#13java%E6%B3%9B%E5%9E%8B%E6%98%AF%E4%BB%80%E4%B9%88%E6%B3%9B%E5%9E%8B%E7%9A%84%E7%B1%BB%E5%9E%8B%E6%93%A6%E9%99%A4%E6%98%AF%E6%80%8E%E4%B9%88%E5%9B%9E%E4%BA%8B)


### Java集合框架

- [Hash表与HashMap](https://github.com/zhpanvip/AndroidNote/wiki/Hash%E8%A1%A8%E4%B8%8EHashMap)
- [HashMap的工作原理](https://github.com/zhpanvip/AndroidNote/wiki/Java%E9%9B%86%E5%90%88%E6%A1%86%E6%9E%B6#1hashmap%E7%9A%84%E5%B7%A5%E4%BD%9C%E5%8E%9F%E7%90%86)
- [为什么HashMap在多线程并发存在死循环的问题，JDK1.8中做了哪些优化？](https://github.com/zhpanvip/AndroidNote/wiki/Java%E9%9B%86%E5%90%88%E6%A1%86%E6%9E%B6#2%E4%B8%BA%E4%BB%80%E4%B9%88hashmap%E5%9C%A8%E5%A4%9A%E7%BA%BF%E7%A8%8B%E5%B9%B6%E5%8F%91%E5%AD%98%E5%9C%A8%E6%AD%BB%E5%BE%AA%E7%8E%AF%E7%9A%84%E9%97%AE%E9%A2%98jdk18%E4%B8%AD%E5%81%9A%E4%BA%86%E5%93%AA%E4%BA%9B%E4%BC%98%E5%8C%96)
- [Hashtable与HashMap有什么区别？](https://github.com/zhpanvip/AndroidNote/wiki/Java%E9%9B%86%E5%90%88%E6%A1%86%E6%9E%B6#3hashtable%E4%B8%8Ehashmap%E6%9C%89%E4%BB%80%E4%B9%88%E5%8C%BA%E5%88%AB)
- [了解ConcurrentHashMap吗？它是怎么实现的?](https://github.com/zhpanvip/AndroidNote/wiki/Java%E9%9B%86%E5%90%88%E6%A1%86%E6%9E%B6#4%E4%BA%86%E8%A7%A3concurrenthashmap%E5%90%97%E5%AE%83%E6%98%AF%E6%80%8E%E4%B9%88%E5%AE%9E%E7%8E%B0%E7%9A%84)
- [可以使用ConcurrentHashMap来代替Hashtable吗？](https://github.com/zhpanvip/AndroidNote/wiki/Java%E9%9B%86%E5%90%88%E6%A1%86%E6%9E%B6#5%E5%8F%AF%E4%BB%A5%E4%BD%BF%E7%94%A8cocurrenthashmap%E6%9D%A5%E4%BB%A3%E6%9B%BFhashtable%E5%90%97)
- [ConcurrentHashMap有什么缺陷吗？](https://github.com/zhpanvip/AndroidNote/wiki/Java%E9%9B%86%E5%90%88%E6%A1%86%E6%9E%B6#6concurrenthashmap%E6%9C%89%E4%BB%80%E4%B9%88%E7%BC%BA%E9%99%B7%E5%90%97)
- [ConcurrentHashMap在JDK 7和8之间的区别](https://github.com/zhpanvip/AndroidNote/wiki/Java%E9%9B%86%E5%90%88%E6%A1%86%E6%9E%B6#7concurrenthashmap%E5%9C%A8jdk-7%E5%92%8C8%E4%B9%8B%E9%97%B4%E7%9A%84%E5%8C%BA%E5%88%AB)
- [Java中HashMap和HashTable的区别？](https://github.com/zhpanvip/AndroidNote/wiki/Java%E9%9B%86%E5%90%88%E6%A1%86%E6%9E%B6#9java%E4%B8%ADhashmap%E5%92%8Chashtable%E7%9A%84%E5%8C%BA%E5%88%AB)
- [HashMap 和 HashSet 的区别](https://github.com/zhpanvip/AndroidNote/wiki/Java%E9%9B%86%E5%90%88%E6%A1%86%E6%9E%B6#10hashmap-%E5%92%8C-hashset-%E7%9A%84%E5%8C%BA%E5%88%AB)
- [请说出 ArrayList和LinkedList的区别？](https://github.com/zhpanvip/AndroidNote/wiki/Java%E9%9B%86%E5%90%88%E6%A1%86%E6%9E%B6#11%E8%AF%B7%E8%AF%B4%E5%87%BA-arraylist%E5%92%8Clinkedlist%E7%9A%84%E5%8C%BA%E5%88%AB)
- [请说出 ArrayList和LinkedList的区别？](https://github.com/zhpanvip/AndroidNote/wiki/Java%E9%9B%86%E5%90%88%E6%A1%86%E6%9E%B6#11%E8%AF%B7%E8%AF%B4%E5%87%BA-arraylist%E5%92%8Clinkedlist%E7%9A%84%E5%8C%BA%E5%88%AB)
- [Java 中 Set 与 List 有什么不同?](https://github.com/zhpanvip/AndroidNote/wiki/Java%E9%9B%86%E5%90%88%E6%A1%86%E6%9E%B6#12java-%E4%B8%AD-set-%E4%B8%8E-list-%E6%9C%89%E4%BB%80%E4%B9%88%E4%B8%8D%E5%90%8C)



### JVM

- [JVM的内存分配](https://github.com/zhpanvip/AndroidNote/wiki/JVM#jvm%E7%9A%84%E5%86%85%E5%AD%98%E5%88%86%E9%85%8D)
- [Java的垃圾回收机制](https://github.com/zhpanvip/AndroidNote/wiki/JVM#java%E7%9A%84%E5%9E%83%E5%9C%BE%E5%9B%9E%E6%94%B6%E6%9C%BA%E5%88%B6)
- [JVM类加载的过程](https://github.com/zhpanvip/AndroidNote/wiki/JVM#jvm%E7%B1%BB%E5%8A%A0%E8%BD%BD%E7%9A%84%E8%BF%87%E7%A8%8B)


### 多线程与并发

- [多线程与并发基础](https://github.com/zhpanvip/AndroidNote/wiki/%E5%A4%9A%E7%BA%BF%E7%A8%8B%E4%B8%8E%E5%B9%B6%E5%8F%91%E5%9F%BA%E7%A1%80)
- [JMM与volatile关键字](https://juejin.cn/post/6967739352784830494)
- [synchronized的实现原理](https://juejin.cn/post/6973571891915128846)
- [synchronized等待与唤醒机制](https://juejin.cn/post/6980002998361522190)
- [AQS的实现原理](https://juejin.cn/post/6975435256111300621#heading-6)
- [ReentrantLock的实现原理](https://juejin.cn/post/6975435256111300621)
- [ReentrantLock等待与唤醒机制](https://juejin.cn/post/6980655421497278495)
- [CAS、Unsafe类以及Automic并发包](https://juejin.cn/post/6977993272538955806)
- [ThreadLoacal的实现原理](https://juejin.cn/post/6986301941269659656)
- [线程池的实现原理](https://juejin.cn/post/6983213662383112206/)
- [Java线程中断机制](https://github.com/zhpanvip/AndroidNote/wiki/Java%E7%BA%BF%E7%A8%8B%E4%B8%AD%E6%96%AD%E6%9C%BA%E5%88%B6)

## 设计模式

- [单利模式](https://github.com/zhpanvip/AndroidNote/wiki/%E5%8D%95%E5%88%A9%E6%A8%A1%E5%BC%8F)
- [动态代理](https://github.com/zhpanvip/AndroidNote/wiki/%E5%8A%A8%E6%80%81%E4%BB%A3%E7%90%86)
- [观察者模式](https://github.com/zhpanvip/AndroidNote/wiki/%E8%A7%82%E5%AF%9F%E8%80%85%E6%A8%A1%E5%BC%8F)
- [策略模式]()
- [命令模式]()

## Kotlin

- [协程实现原理](https://github.com/zhpanvip/AndroidNote/wiki/%E5%8D%8F%E7%A8%8B%E5%AE%9E%E7%8E%B0%E5%8E%9F%E7%90%86)
- [高阶函数实现原理](https://github.com/zhpanvip/AndroidNote/wiki/%E9%AB%98%E9%98%B6%E5%87%BD%E6%95%B0%E5%AE%9E%E7%8E%B0%E5%8E%9F%E7%90%86)

## Android

### Android基础知识

- [Android基础知识汇总](https://github.com/zhpanvip/AndroidNote/wiki/Android%E5%9F%BA%E7%A1%80%E7%9F%A5%E8%AF%86%E6%B1%87%E6%80%BB)
- [MVC、MVP与MVVM](https://github.com/zhpanvip/AndroidNote/wiki/MVC%E3%80%81MVP%E4%B8%8EMVVM)
- [SparseArray实现原理](https://github.com/zhpanvip/AndroidNote/wiki/SparseArray%E5%AE%9E%E7%8E%B0%E5%8E%9F%E7%90%86)
- [ArrayMap的实现原理](https://github.com/zhpanvip/AndroidNote/wiki/ArrayMap%E7%9A%84%E5%AE%9E%E7%8E%B0%E5%8E%9F%E7%90%86)
- [SharedPreferences](https://github.com/zhpanvip/AndroidNote/wiki/SharedPreferences)
- [Bitmap](https://github.com/zhpanvip/AndroidNote/wiki/Bitmap)
- [Activity的启动模式](https://github.com/zhpanvip/AndroidNote/wiki/Activity%E7%9A%84%E5%90%AF%E5%8A%A8%E6%A8%A1%E5%BC%8F)
- [Fragment核心原理](https://github.com/zhpanvip/AndroidNote/wiki/Fragment%E6%A0%B8%E5%BF%83%E5%8E%9F%E7%90%86)
- [组件化WebView架构搭建](https://github.com/zhpanvip/AndroidNote/wiki/%E7%BB%84%E4%BB%B6%E5%8C%96WebView%E6%9E%B6%E6%9E%84%E6%90%AD%E5%BB%BA)

### Android消息机制

- [简述Handler的实现原理](https://github.com/zhpanvip/AndroidNote/wiki/Handler%E7%9B%B8%E5%85%B3#1%E7%AE%80%E8%BF%B0handler%E7%9A%84%E5%AE%9E%E7%8E%B0%E5%8E%9F%E7%90%86)
- [一个线程有几个Handler？一个线程有几个Looper？如何保证？](https://github.com/zhpanvip/AndroidNote/wiki/Handler%E7%9B%B8%E5%85%B3#2%E4%B8%80%E4%B8%AA%E7%BA%BF%E7%A8%8B%E6%9C%89%E5%87%A0%E4%B8%AAhandler%E4%B8%80%E4%B8%AA%E7%BA%BF%E7%A8%8B%E6%9C%89%E5%87%A0%E4%B8%AAlooper%E5%A6%82%E4%BD%95%E4%BF%9D%E8%AF%81)
- [Handler线程是如何切换的？](https://github.com/zhpanvip/AndroidNote/wiki/Handler%E7%9B%B8%E5%85%B3#3handler%E7%BA%BF%E7%A8%8B%E6%98%AF%E5%A6%82%E4%BD%95%E5%88%87%E6%8D%A2%E7%9A%84)
- [Handler内存泄漏的原因是什么？如何解决?](https://github.com/zhpanvip/AndroidNote/wiki/Handler%E7%9B%B8%E5%85%B3#4handler%E5%86%85%E5%AD%98%E6%B3%84%E6%BC%8F%E7%9A%84%E5%8E%9F%E5%9B%A0%E6%98%AF%E4%BB%80%E4%B9%88%E5%A6%82%E4%BD%95%E8%A7%A3%E5%86%B3)
- [子线程中使用Looper应该注意什么？有什么用？](https://github.com/zhpanvip/AndroidNote/wiki/Handler%E7%9B%B8%E5%85%B3#5%E5%AD%90%E7%BA%BF%E7%A8%8B%E4%B8%AD%E4%BD%BF%E7%94%A8looper%E5%BA%94%E8%AF%A5%E6%B3%A8%E6%84%8F%E4%BB%80%E4%B9%88%E6%9C%89%E4%BB%80%E4%B9%88%E7%94%A8)
- [MessageQueue是如何保证线程安全的？](https://github.com/zhpanvip/AndroidNote/wiki/Handler%E7%9B%B8%E5%85%B3#6messagequeue%E6%98%AF%E5%A6%82%E4%BD%95%E4%BF%9D%E8%AF%81%E7%BA%BF%E7%A8%8B%E5%AE%89%E5%85%A8%E7%9A%84)
- [我们使用Message的时候如何创建它？](https://github.com/zhpanvip/AndroidNote/wiki/Handler%E7%9B%B8%E5%85%B3#7%E6%88%91%E4%BB%AC%E4%BD%BF%E7%94%A8message%E7%9A%84%E6%97%B6%E5%80%99%E5%A6%82%E4%BD%95%E5%88%9B%E5%BB%BA%E5%AE%83)
- [Looper死循环为什么不会导致应用卡死？](https://github.com/zhpanvip/AndroidNote/wiki/Handler%E7%9B%B8%E5%85%B3#8looper%E6%AD%BB%E5%BE%AA%E7%8E%AF%E4%B8%BA%E4%BB%80%E4%B9%88%E4%B8%8D%E4%BC%9A%E5%AF%BC%E8%87%B4%E5%BA%94%E7%94%A8%E5%8D%A1%E6%AD%BB)
- [能不能让一个Message被加急处理？](https://github.com/zhpanvip/AndroidNote/wiki/Handler%E7%9B%B8%E5%85%B3#9%E8%83%BD%E4%B8%8D%E8%83%BD%E8%AE%A9%E4%B8%80%E4%B8%AAmessage%E8%A2%AB%E5%8A%A0%E6%80%A5%E5%A4%84%E7%90%86)
- [Handler的同步屏障是什么？](https://github.com/zhpanvip/AndroidNote/wiki/Handler%E7%9B%B8%E5%85%B3#10handler%E7%9A%84%E5%90%8C%E6%AD%A5%E5%B1%8F%E9%9A%9C%E6%98%AF%E4%BB%80%E4%B9%88)
- [Handler的阻塞唤醒机制是什么？](https://github.com/zhpanvip/AndroidNote/wiki/Handler%E7%9B%B8%E5%85%B3#11handler%E7%9A%84%E9%98%BB%E5%A1%9E%E5%94%A4%E9%86%92%E6%9C%BA%E5%88%B6%E6%98%AF%E4%BB%80%E4%B9%88)
- [ThreadLocal的实现原理](https://github.com/zhpanvip/AndroidNote/wiki/ThreadLoacal%E7%9A%84%E5%AE%9E%E7%8E%B0%E5%8E%9F%E7%90%86)
- [HandlerThread是什么？](https://github.com/zhpanvip/AndroidNote/wiki/HandlerThread%E5%AE%9E%E7%8E%B0%E5%8E%9F%E7%90%86)
- [IntentService是什么？](https://github.com/zhpanvip/AndroidNote/wiki/IntentService%E5%AE%9E%E7%8E%B0%E5%8E%9F%E7%90%86)
- [IdleHandler是什么？](https://github.com/zhpanvip/AndroidNote/wiki/Handler%E7%9B%B8%E5%85%B3#15idlehandler%E6%98%AF%E4%BB%80%E4%B9%88)

### Framework

- [Binder与AIDL](https://github.com/zhpanvip/AndroidNote/wiki/Binder%E4%B8%8EAIDL)
- [Binder实现原理](https://github.com/zhpanvip/AndroidNote/wiki/Binder%E6%9C%BA%E5%88%B6%E5%8E%9F%E7%90%86)
- [Android系统启动流程](https://github.com/zhpanvip/AndroidNote/wiki/Android%E7%B3%BB%E7%BB%9F%E5%90%AF%E5%8A%A8%E6%B5%81%E7%A8%8B)
- [InputManagerService](https://github.com/zhpanvip/AndroidNote/wiki/InputManagerService)
- [WindowManagerService](https://github.com/zhpanvip/AndroidNote/wiki/WMS%E6%A0%B8%E5%BF%83%E5%88%86%E6%9E%90)
- [Choreographer详解](https://github.com/zhpanvip/AndroidNote/wiki/Choreographer%E8%AF%A6%E8%A7%A3)
- [SurfaceFlinger](https://github.com/zhpanvip/AndroidNote/wiki/SurfaceFlinger)
- [ViewRootImpl](https://github.com/zhpanvip/AndroidNote/wiki/ViewRootImpl)
- [ActivityManagerService](https://github.com/zhpanvip/AndroidNote/wiki/AMS%E6%A0%B8%E5%BF%83%E5%88%86%E6%9E%90)
- [APP启动流程](https://github.com/zhpanvip/AndroidNote/wiki/App%E7%9A%84%E5%90%AF%E5%8A%A8%E6%B5%81%E7%A8%8B)
- [PMS安装与签名校验](https://github.com/zhpanvip/AndroidNote/wiki/PMS%E5%AE%89%E8%A3%85%E4%B8%8E%E7%AD%BE%E5%90%8D%E6%A0%A1%E9%AA%8C)
- [Dalvik与ART](https://github.com/zhpanvip/AndroidNote/wiki/Dalvik%E4%B8%8EART)

  

### View事件分发机制

- [ViewRootImpl](https://github.com/zhpanvip/AndroidNote/wiki/ViewRootImpl)
- [事件分发机制流程](https://github.com/zhpanvip/AndroidNote/wiki/View%E4%BA%8B%E4%BB%B6%E5%88%86%E5%8F%91%E6%9C%BA%E5%88%B6)
- [ViewGroup中的mFirstTouchTarget是一个什么东西，它有什么作用？](https://github.com/zhpanvip/AndroidNote/wiki/View%E4%BA%8B%E4%BB%B6%E5%88%86%E5%8F%91%E6%9C%BA%E5%88%B6#1viewgroup%E4%B8%AD%E7%9A%84mfirsttouchtarget%E6%98%AF%E4%B8%80%E4%B8%AA%E4%BB%80%E4%B9%88%E4%B8%9C%E8%A5%BF%E5%AE%83%E6%9C%89%E4%BB%80%E4%B9%88%E4%BD%9C%E7%94%A8)
- [如果在ViewGroup中拦截了ACTION_DOWN事件会怎样？](https://github.com/zhpanvip/AndroidNote/wiki/View%E4%BA%8B%E4%BB%B6%E5%88%86%E5%8F%91%E6%9C%BA%E5%88%B6#2%E5%A6%82%E6%9E%9C%E5%9C%A8viewgroup%E4%B8%AD%E6%8B%A6%E6%88%AA%E4%BA%86action_down%E4%BA%8B%E4%BB%B6%E4%BC%9A%E6%80%8E%E6%A0%B7)
- [为什么设置了onTouchListener后onClickListener不会被调用？](https://github.com/zhpanvip/AndroidNote/wiki/View%E4%BA%8B%E4%BB%B6%E5%88%86%E5%8F%91%E6%9C%BA%E5%88%B6#3%E4%B8%BA%E4%BB%80%E4%B9%88%E8%AE%BE%E7%BD%AE%E4%BA%86ontouchlistener%E5%90%8Eonclicklistener%E4%B8%8D%E4%BC%9A%E8%A2%AB%E8%B0%83%E7%94%A8)
- [为什么一个View设置了setOnTouchListener会有提示没有引用performClick方法的警告？](https://github.com/zhpanvip/AndroidNote/wiki/View%E4%BA%8B%E4%BB%B6%E5%88%86%E5%8F%91%E6%9C%BA%E5%88%B6#3%E4%B8%BA%E4%BB%80%E4%B9%88%E8%AE%BE%E7%BD%AE%E4%BA%86ontouchlistener%E5%90%8Eonclicklistener%E4%B8%8D%E4%BC%9A%E8%A2%AB%E8%B0%83%E7%94%A8)



### Android屏幕刷新机制

- [WindowManagerService](https://github.com/zhpanvip/AndroidNote/wiki/WMS%E6%A0%B8%E5%BF%83%E5%88%86%E6%9E%90)
- [屏幕刷新机制概述](https://github.com/zhpanvip/AndroidNote/wiki/%E5%B1%8F%E5%B9%95%E5%88%B7%E6%96%B0%E6%9C%BA%E5%88%B6#%E4%BA%8Cui%E6%B8%B2%E6%9F%93%E6%B5%81%E7%A8%8B)
- [UI渲染流程](https://github.com/zhpanvip/AndroidNote/wiki/%E5%B1%8F%E5%B9%95%E5%88%B7%E6%96%B0%E6%9C%BA%E5%88%B6#%E4%BA%8Cui%E6%B8%B2%E6%9F%93%E6%B5%81%E7%A8%8B)
- [Choreographer详解](https://github.com/zhpanvip/AndroidNote/wiki/Choreographer%E8%AF%A6%E8%A7%A3)
- [requestLayout与invalidate](https://github.com/zhpanvip/AndroidNote/wiki/requestLayout%E4%B8%8Einvalidate)
- [SurfaceFlinger](https://github.com/zhpanvip/AndroidNote/wiki/SurfaceFlinger)
- [相关面试题](https://github.com/zhpanvip/AndroidNote/wiki/%E5%B1%8F%E5%B9%95%E5%88%B7%E6%96%B0%E6%9C%BA%E5%88%B6#%E4%B8%89%E7%9B%B8%E5%85%B3%E9%9D%A2%E8%AF%95%E9%A2%98)

### View的绘制流程

- [简述View的绘制流程](https://github.com/zhpanvip/AndroidNote/wiki/View%E7%9A%84%E7%BB%98%E5%88%B6%E6%B5%81%E7%A8%8B#1view%E7%9A%84%E7%BB%98%E5%88%B6%E6%B5%81%E7%A8%8B%E6%A6%82%E8%BF%B0)
- [LayoutInflater](https://github.com/zhpanvip/AndroidNote/wiki/LayoutInflater)
- [MeasureSpec是什么？](https://github.com/zhpanvip/AndroidNote/wiki/View%E7%9A%84%E7%BB%98%E5%88%B6%E6%B5%81%E7%A8%8B#2measurespec%E6%98%AF%E4%BB%80%E4%B9%88)

### Activity启动

- [ActivityManagerService](https://github.com/zhpanvip/AndroidNote/wiki/AMS%E6%A0%B8%E5%BF%83%E5%88%86%E6%9E%90)
- [ActivityThread](https://github.com/zhpanvip/AndroidNote/wiki/ActivityThread)
- [Instrumentation](https://github.com/zhpanvip/AndroidNote/wiki/Instrumentation)
- [Activity启动流程](https://github.com/zhpanvip/AndroidNote/wiki/App%E7%9A%84%E5%90%AF%E5%8A%A8%E6%B5%81%E7%A8%8B)


### 性能优化

- [内存优化策略](https://github.com/zhpanvip/AndroidNote/wiki/%E5%86%85%E5%AD%98%E4%BC%98%E5%8C%96)
- [UI界面及卡顿优化](https://github.com/zhpanvip/AndroidNote/wiki/UI%E7%95%8C%E9%9D%A2%E5%8F%8A%E5%8D%A1%E9%A1%BF%E4%BC%98%E5%8C%96)
- [App启动优化](https://github.com/zhpanvip/AndroidNote/wiki/%E5%90%AF%E5%8A%A8%E4%BC%98%E5%8C%96)
- [ANR问题](https://github.com/zhpanvip/AndroidNote/wiki/ANR%E9%97%AE%E9%A2%98%E4%BC%98%E5%8C%96)
- [包体积优化](https://github.com/zhpanvip/AndroidNote/wiki/%E5%8C%85%E4%BD%93%E7%A7%AF%E4%BC%98%E5%8C%96)
- [APK打包流程](https://github.com/zhpanvip/AndroidNote/wiki/APK%E7%9A%84%E6%89%93%E5%8C%85%E6%B5%81%E7%A8%8B)
- [电池电量优化]()
- [Android屏幕适配](https://github.com/zhpanvip/AndroidNote/wiki/%E5%B1%8F%E5%B9%95%E9%80%82%E9%85%8D)
- [线上性能监控1--线上监控切入点](https://github.com/zhpanvip/AndroidNote/wiki/%E7%BA%BF%E4%B8%8A%E6%80%A7%E8%83%BD%E7%9B%91%E6%8E%A7)
- [线上性能监控2--Matrix实现原理](https://github.com/zhpanvip/AndroidNote/wiki/%E7%BA%BF%E4%B8%8A%E6%80%A7%E8%83%BD%E7%9B%91%E6%8E%A72-Matrix%E5%AE%9E%E7%8E%B0%E5%8E%9F%E7%90%86)



### Jetpack&系统View

- [ViewModel的实现原理](https://github.com/zhpanvip/AndroidNote/wiki/ViewModel%E7%9A%84%E5%AE%9E%E7%8E%B0%E5%8E%9F%E7%90%86)
- [WorkManager的实现原理](https://github.com/zhpanvip/AndroidNote/wiki/WorkManager%E7%9A%84%E5%AE%9E%E7%8E%B0%E5%8E%9F%E7%90%86)
- [Lifecycle实现原理](https://github.com/zhpanvip/AndroidNote/wiki/Lifecycle%E5%AE%9E%E7%8E%B0%E5%8E%9F%E7%90%86)
- [RecyclerView实现原理](https://github.com/zhpanvip/AndroidNote/wiki/RecyclerView%E5%AE%9E%E7%8E%B0%E5%8E%9F%E7%90%86)

### 第三方框架实现原理

- [Glide实现原理](https://github.com/zhpanvip/AndroidNote/wiki/Glide%E5%AE%9E%E7%8E%B0%E5%8E%9F%E7%90%86)
- [OkHttp实现原理](https://github.com/zhpanvip/AndroidNote/wiki/OKHttp%E5%AE%9E%E7%8E%B0%E5%8E%9F%E7%90%86)
- [Retrofit实现原理](https://github.com/zhpanvip/AndroidNote/wiki/Retrofit%E5%AE%9E%E7%8E%B0%E5%8E%9F%E7%90%86)
- [RxJava实现原理](https://github.com/zhpanvip/AndroidNote/wiki/RxJava%E5%AE%9E%E7%8E%B0%E5%8E%9F%E7%90%86)
- [LeakCanary实现原理](https://github.com/zhpanvip/AndroidNote/wiki/LeakCanary-%E5%AE%9E%E7%8E%B0%E5%8E%9F%E7%90%86)
- [ButterKnife实现原理](https://github.com/zhpanvip/AndroidNote/wiki/Butterknife%E5%AE%9E%E7%8E%B0%E5%8E%9F%E7%90%86)
- [ARouter实现原理](https://github.com/zhpanvip/AndroidNote/wiki/ARouter%E5%AE%9E%E7%8E%B0%E5%8E%9F%E7%90%86)
- [Tinker实现原理](https://github.com/zhpanvip/AndroidNote/wiki/Tinker%E5%AE%9E%E7%8E%B0%E5%8E%9F%E7%90%86)




### 计算机网络

- [简述TCP/IP协议](https://github.com/zhpanvip/AndroidNote/wiki/%E8%AE%A1%E7%AE%97%E6%9C%BA%E7%BD%91%E7%BB%9C#tcpip%E5%8D%8F%E8%AE%AE)
- [TCP与UDP](https://github.com/zhpanvip/AndroidNote/wiki/TCP%E4%B8%8EUDP)
  - [TCP协议与UDP协议的区别](https://github.com/zhpanvip/AndroidNote/wiki/TCP%E4%B8%8EUDP#tcp%E5%8D%8F%E8%AE%AE%E4%B8%8Eudp%E5%8D%8F%E8%AE%AE%E7%9A%84%E5%8C%BA%E5%88%AB)
  - [TCP协议的三次握手](https://github.com/zhpanvip/AndroidNote/wiki/TCP%E4%B8%8EUDP#tcp%E5%8D%8F%E8%AE%AE%E7%9A%84%E4%B8%89%E6%AC%A1%E6%8F%A1%E6%89%8B)
  - [TCP协议的四次挥手](https://github.com/zhpanvip/AndroidNote/wiki/TCP%E4%B8%8EUDP#tcp%E5%8D%8F%E8%AE%AE%E7%9A%84%E5%9B%9B%E6%AC%A1%E6%8C%A5%E6%89%8B)
- [IP 协议相关技术](https://github.com/zhpanvip/AndroidNote/wiki/%E8%AE%A1%E7%AE%97%E6%9C%BA%E7%BD%91%E7%BB%9C#ip-%E5%8D%8F%E8%AE%AE%E7%9B%B8%E5%85%B3%E6%8A%80%E6%9C%AF)
- [网络I/O模型](https://github.com/zhpanvip/AndroidNote/wiki/%E7%BD%91%E7%BB%9CI-O%E6%A8%A1%E5%9E%8B)
- [HTTP协议](https://github.com/zhpanvip/AndroidNote/wiki/Http%E5%8D%8F%E8%AE%AE)
- [HTTPS的实现原理](https://github.com/zhpanvip/AndroidNote/wiki/HTTPS%E5%AE%9E%E7%8E%B0%E5%8E%9F%E7%90%86)
- [Socket](https://github.com/zhpanvip/AndroidNote/wiki/Socket)

### 算法

#### [排序算法](https://github.com/zhpanvip/AndroidNote/wiki/%E6%8E%92%E5%BA%8F%E7%AE%97%E6%B3%95)
  - [1.快速排序](https://github.com/zhpanvip/AndroidNote/wiki/%E6%8E%92%E5%BA%8F%E7%AE%97%E6%B3%95#1%E5%BF%AB%E9%80%9F%E6%8E%92%E5%BA%8F)
  - [2.归并排序](https://github.com/zhpanvip/AndroidNote/wiki/%E6%8E%92%E5%BA%8F%E7%AE%97%E6%B3%95#2%E5%BD%92%E5%B9%B6%E6%8E%92%E5%BA%8F)
  - [3.冒泡排序](https://github.com/zhpanvip/AndroidNote/wiki/%E6%8E%92%E5%BA%8F%E7%AE%97%E6%B3%95#3%E5%86%92%E6%B3%A1%E6%8E%92%E5%BA%8F)
#### [查找相关](https://github.com/zhpanvip/AndroidNote/wiki/%E6%9F%A5%E6%89%BE%E7%AE%97%E6%B3%95)
  - [35. 搜索插入位置](https://github.com/zhpanvip/AndroidNote/wiki/%E6%9F%A5%E6%89%BE%E7%AE%97%E6%B3%95#35-%E6%90%9C%E7%B4%A2%E6%8F%92%E5%85%A5%E4%BD%8D%E7%BD%AE)
  - [278. 第一个错误的版本](https://github.com/zhpanvip/AndroidNote/wiki/%E6%9F%A5%E6%89%BE%E7%AE%97%E6%B3%95#278-%E7%AC%AC%E4%B8%80%E4%B8%AA%E9%94%99%E8%AF%AF%E7%9A%84%E7%89%88%E6%9C%AC)
  - [704. 二分查找](https://github.com/zhpanvip/AndroidNote/wiki/%E6%9F%A5%E6%89%BE%E7%AE%97%E6%B3%95#leetcode-704-%E4%BA%8C%E5%88%86%E6%9F%A5%E6%89%BE)
  - [剑指 Offer 53 - II. 0～n-1中缺失的数字](https://github.com/zhpanvip/AndroidNote/wiki/%E6%9F%A5%E6%89%BE%E7%AE%97%E6%B3%95#%E5%89%91%E6%8C%87-offer-53---ii-0n-1%E4%B8%AD%E7%BC%BA%E5%A4%B1%E7%9A%84%E6%95%B0%E5%AD%97)
#### [链表相关](https://github.com/zhpanvip/AndroidNote/wiki/%E9%93%BE%E8%A1%A8%E7%9B%B8%E5%85%B3%E7%AE%97%E6%B3%95)

  - [19.删除链表的倒数第 N 个结点](https://github.com/zhpanvip/AndroidNote/wiki/%E9%93%BE%E8%A1%A8%E7%9B%B8%E5%85%B3%E7%AE%97%E6%B3%95#19-%E5%88%A0%E9%99%A4%E9%93%BE%E8%A1%A8%E7%9A%84%E5%80%92%E6%95%B0%E7%AC%AC-n-%E4%B8%AA%E7%BB%93%E7%82%B9)
  - [21. 合并两个有序链表](https://github.com/zhpanvip/AndroidNote/wiki/%E9%93%BE%E8%A1%A8%E7%9B%B8%E5%85%B3%E7%AE%97%E6%B3%95#leetcode-21-%E5%90%88%E5%B9%B6%E4%B8%A4%E4%B8%AA%E6%9C%89%E5%BA%8F%E9%93%BE%E8%A1%A8)
  - [24. 两两交换链表中的节点](https://github.com/zhpanvip/AndroidNote/wiki/%E9%93%BE%E8%A1%A8%E7%9B%B8%E5%85%B3%E7%AE%97%E6%B3%95#24-%E4%B8%A4%E4%B8%A4%E4%BA%A4%E6%8D%A2%E9%93%BE%E8%A1%A8%E4%B8%AD%E7%9A%84%E8%8A%82%E7%82%B9)
  - [61. 旋转链表](https://github.com/zhpanvip/AndroidNote/wiki/%E9%93%BE%E8%A1%A8%E7%9B%B8%E5%85%B3%E7%AE%97%E6%B3%95#61-%E6%97%8B%E8%BD%AC%E9%93%BE%E8%A1%A8)
  - [86. 分隔链表](https://github.com/zhpanvip/AndroidNote/wiki/%E9%93%BE%E8%A1%A8%E7%9B%B8%E5%85%B3%E7%AE%97%E6%B3%95#86-%E5%88%86%E9%9A%94%E9%93%BE%E8%A1%A8)
  - [92. 反转链表 II](https://github.com/zhpanvip/AndroidNote/wiki/%E9%93%BE%E8%A1%A8%E7%9B%B8%E5%85%B3%E7%AE%97%E6%B3%95#92-%E5%8F%8D%E8%BD%AC%E9%93%BE%E8%A1%A8-ii)
  - [141. 环形链表](https://github.com/zhpanvip/AndroidNote/wiki/%E9%93%BE%E8%A1%A8%E7%9B%B8%E5%85%B3%E7%AE%97%E6%B3%95#141-%E7%8E%AF%E5%BD%A2%E9%93%BE%E8%A1%A8)
  - [206. 反转链表](https://github.com/zhpanvip/AndroidNote/wiki/%E9%93%BE%E8%A1%A8%E7%9B%B8%E5%85%B3%E7%AE%97%E6%B3%95#206-%E5%8F%8D%E8%BD%AC%E9%93%BE%E8%A1%A8)
  - [206 反转链表 扩展](https://github.com/zhpanvip/AndroidNote/wiki/%E9%93%BE%E8%A1%A8%E7%9B%B8%E5%85%B3%E7%AE%97%E6%B3%95#206-%E5%8F%8D%E8%BD%AC%E9%93%BE%E8%A1%A8-%E6%89%A9%E5%B1%95)
  - [234. 回文链表](https://github.com/zhpanvip/AndroidNote/wiki/%E9%93%BE%E8%A1%A8%E7%9B%B8%E5%85%B3%E7%AE%97%E6%B3%95#234-%E5%9B%9E%E6%96%87%E9%93%BE%E8%A1%A8)
  - [237. 删除链表中的节点](https://github.com/zhpanvip/AndroidNote/wiki/%E9%93%BE%E8%A1%A8%E7%9B%B8%E5%85%B3%E7%AE%97%E6%B3%95#237-%E5%88%A0%E9%99%A4%E9%93%BE%E8%A1%A8%E4%B8%AD%E7%9A%84%E8%8A%82%E7%82%B9)
  - [445. 两数相加 II](https://github.com/zhpanvip/AndroidNote/wiki/%E9%93%BE%E8%A1%A8%E7%9B%B8%E5%85%B3%E7%AE%97%E6%B3%95#445-%E4%B8%A4%E6%95%B0%E7%9B%B8%E5%8A%A0-ii)
  - [面试题 02.02. 返回倒数第 k 个节点](https://github.com/zhpanvip/AndroidNote/wiki/%E9%93%BE%E8%A1%A8%E7%9B%B8%E5%85%B3%E7%AE%97%E6%B3%95#%E9%9D%A2%E8%AF%95%E9%A2%98-0202-%E8%BF%94%E5%9B%9E%E5%80%92%E6%95%B0%E7%AC%AC-k-%E4%B8%AA%E8%8A%82%E7%82%B9)
  - [面试题 02.08. 环路检测](https://github.com/zhpanvip/AndroidNote/wiki/%E9%93%BE%E8%A1%A8%E7%9B%B8%E5%85%B3%E7%AE%97%E6%B3%95#%E9%9D%A2%E8%AF%95%E9%A2%98-0208-%E7%8E%AF%E8%B7%AF%E6%A3%80%E6%B5%8B)
  - [剑指 Offer 06. 从尾到头打印链表](https://github.com/zhpanvip/AndroidNote/wiki/%E9%93%BE%E8%A1%A8%E7%9B%B8%E5%85%B3%E7%AE%97%E6%B3%95#%E5%89%91%E6%8C%87-offer-06-%E4%BB%8E%E5%B0%BE%E5%88%B0%E5%A4%B4%E6%89%93%E5%8D%B0%E9%93%BE%E8%A1%A8)
  - [剑指 Offer 22. 链表中倒数第k个节点](https://github.com/zhpanvip/AndroidNote/wiki/%E9%93%BE%E8%A1%A8%E7%9B%B8%E5%85%B3%E7%AE%97%E6%B3%95#%E5%89%91%E6%8C%87-offer-22-%E9%93%BE%E8%A1%A8%E4%B8%AD%E5%80%92%E6%95%B0%E7%AC%ACk%E4%B8%AA%E8%8A%82%E7%82%B9)
  - [剑指 Offer 35. 复杂链表的复制](https://github.com/zhpanvip/AndroidNote/wiki/%E9%93%BE%E8%A1%A8%E7%9B%B8%E5%85%B3%E7%AE%97%E6%B3%95#%E5%89%91%E6%8C%87-offer-35-%E5%A4%8D%E6%9D%82%E9%93%BE%E8%A1%A8%E7%9A%84%E5%A4%8D%E5%88%B6---%E5%90%8C-leetcode-138-%E5%A4%8D%E5%88%B6%E5%B8%A6%E9%9A%8F%E6%9C%BA%E6%8C%87%E9%92%88%E7%9A%84%E9%93%BE%E8%A1%A8)

#### [数组相关](https://github.com/zhpanvip/AndroidNote/wiki/%E6%95%B0%E7%BB%84%E7%9B%B8%E5%85%B3%E7%AE%97%E6%B3%95)
  - [1. 两数之和](https://github.com/zhpanvip/AndroidNote/wiki/%E6%95%B0%E7%BB%84%E7%9B%B8%E5%85%B3%E7%AE%97%E6%B3%95#1-%E4%B8%A4%E6%95%B0%E4%B9%8B%E5%92%8C)
  - [75. 颜色分类](https://github.com/zhpanvip/AndroidNote/wiki/%E6%95%B0%E7%BB%84%E7%9B%B8%E5%85%B3%E7%AE%97%E6%B3%95#75-%E9%A2%9C%E8%89%B2%E5%88%86%E7%B1%BB)
  - [124.验证回文串](https://github.com/zhpanvip/AndroidNote/wiki/%E6%95%B0%E7%BB%84%E7%9B%B8%E5%85%B3%E7%AE%97%E6%B3%95#125-%E9%AA%8C%E8%AF%81%E5%9B%9E%E6%96%87%E4%B8%B2)
  - [167. 两数之和 II - 输入有序数组](https://github.com/zhpanvip/AndroidNote/wiki/%E6%95%B0%E7%BB%84%E7%9B%B8%E5%85%B3%E7%AE%97%E6%B3%95#167-%E4%B8%A4%E6%95%B0%E4%B9%8B%E5%92%8C-ii---%E8%BE%93%E5%85%A5%E6%9C%89%E5%BA%8F%E6%95%B0%E7%BB%84)
  - [189.旋转数组](https://github.com/zhpanvip/AndroidNote/wiki/%E6%95%B0%E7%BB%84%E7%9B%B8%E5%85%B3%E7%AE%97%E6%B3%95#189-%E6%97%8B%E8%BD%AC%E6%95%B0%E7%BB%84)
  - [283.移动0](https://github.com/zhpanvip/AndroidNote/wiki/%E6%95%B0%E7%BB%84%E7%9B%B8%E5%85%B3%E7%AE%97%E6%B3%95#283-%E7%A7%BB%E5%8A%A8%E9%9B%B6)
  - [303.区域和检索 - 数组不可变](https://github.com/zhpanvip/AndroidNote/wiki/%E6%95%B0%E7%BB%84%E7%9B%B8%E5%85%B3%E7%AE%97%E6%B3%95#303-%E5%8C%BA%E5%9F%9F%E5%92%8C%E6%A3%80%E7%B4%A2---%E6%95%B0%E7%BB%84%E4%B8%8D%E5%8F%AF%E5%8F%98)
  - [643.有序数组的平方](https://github.com/zhpanvip/AndroidNote/wiki/%E6%95%B0%E7%BB%84%E7%9B%B8%E5%85%B3%E7%AE%97%E6%B3%95#977--%E6%9C%89%E5%BA%8F%E6%95%B0%E7%BB%84%E7%9A%84%E5%B9%B3%E6%96%B9)
#### [二叉树](https://github.com/zhpanvip/AndroidNote/wiki/%E4%BA%8C%E5%8F%89%E6%A0%91%E7%9B%B8%E5%85%B3%E7%AE%97%E6%B3%95)
#### [字符串](https://github.com/zhpanvip/AndroidNote/wiki/%E5%AD%97%E7%AC%A6%E4%B8%B2%E7%9B%B8%E5%85%B3%E7%AE%97%E6%B3%95)
  - [125. 验证回文串](https://github.com/zhpanvip/AndroidNote/wiki/%E5%AD%97%E7%AC%A6%E4%B8%B2%E7%9B%B8%E5%85%B3%E7%AE%97%E6%B3%95#125-%E9%AA%8C%E8%AF%81%E5%9B%9E%E6%96%87%E4%B8%B2/)
  - [20.有效括号](https://github.com/zhpanvip/AndroidNote/wiki/%E5%AD%97%E7%AC%A6%E4%B8%B2%E7%9B%B8%E5%85%B3%E7%AE%97%E6%B3%95#20-%E6%9C%89%E6%95%88%E7%9A%84%E6%8B%AC%E5%8F%B7)
  - [344.反转字符串](https://github.com/zhpanvip/AndroidNote/wiki/%E5%AD%97%E7%AC%A6%E4%B8%B2%E7%9B%B8%E5%85%B3%E7%AE%97%E6%B3%95#344-%E5%8F%8D%E8%BD%AC%E5%AD%97%E7%AC%A6%E4%B8%B2)
  - [557.反转字符串中的单词 III](https://github.com/zhpanvip/AndroidNote/wiki/%E5%AD%97%E7%AC%A6%E4%B8%B2%E7%9B%B8%E5%85%B3%E7%AE%97%E6%B3%95#557-%E5%8F%8D%E8%BD%AC%E5%AD%97%E7%AC%A6%E4%B8%B2%E4%B8%AD%E7%9A%84%E5%8D%95%E8%AF%8D-iii)


#### [递归](https://github.com/zhpanvip/AndroidNote/wiki/%E9%80%92%E5%BD%92%E7%AE%97%E6%B3%95)

### 其它

- [HR常见问题](https://github.com/zhpanvip/AndroidNote/wiki/HR%E9%9D%A2%E5%B8%B8%E9%97%AE%E9%97%AE%E9%A2%98)