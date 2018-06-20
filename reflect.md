## 1. 反射定义
反射：在计算机科学中，反射是指计算机程序在运行时（Run time）可以访问、检测和修改它本身状态或行为的一种能力。
## 2. Java 反射使用
2.1 通过反射获取类：Class.forName("package.className")，klass.getClass()和 Kclass.class;

2.2 通过反射可以获取该类得所有的构造函数、方法、变量和注解

2.3 通过反射可以执行方法

2.4 反射中常有得异常：NoSuchMethodException, SecurityException

## 3. 反射应用场景
3.1 Json 与 Java 之间转换

3.2 参数配置化，动态执行代码

## 4. 反射优点，缺点.
4.1 性能和内存隐患：https://mp.weixin.qq.com/s/5H6UHcP6kvR2X5hTj_SBjA?

4.2 更加动态性，可扩展性
## Java 加载类机制
![alt 类加载机制](https://pic4.zhimg.com/80/v2-4face8109e0d52ef5894c41c69e4ec6b_hd.jpg)

## 延申阅读
https://www.guru99.com/java-reflection-api.html
