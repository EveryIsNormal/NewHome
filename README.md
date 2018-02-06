# I/O模型

## 同步、异步、阻塞和非阻塞
```
同步：一直等……直到结束。
异步：打了个广告就跑了，就等别人来找他了。
阻塞：一直等……直到结束。
非阻塞：发现没有准备好，等会再来。
```
## 同步阻塞、同步非阻塞、异步阻塞和异步非阻塞
```
```
## select、poll和epoll
**1. fd: File Descriptor(文件描述符)**
**2. select 模型**
  ![select](https://github.com/xiaobaojiang/xiaobaojiang.github.io/blob/master/trace.md)

# [Vertx](vertx.io)
**1. Vertx 是什么**
```
Eclipse Vert.x is event driven and non blocking. This means your app can handle a lot of concurrency 
using a small number of kernel threads. Vert.x lets your app scale with minimal hardware.
```
**2. Vertx 与 Verticle 关系**

1. Vertx Deploy Verticle

2. Vertx apply the event loop threads

3. Verticle like an actor in Actor Model.
```
Vert.x comes with a simple, scalable, actor-like deployment and concurrency model out of the box that
you can use to save you writing your own.
This model is entirely optional and Vert.x does not force you to create your applications in this way 
if you don’t want to..
The model does not claim to be a strict actor-model implementation, but it does share similarities especially 
with respect to concurrency, scaling and deployment.
To use this model, you write your code as set of verticles.
Verticles are chunks of code that get deployed and run by Vert.x. A Vert.x instance maintains N event loop threads 
(where N by default is core*2) by default. Verticles can be written in any of the languages that
Vert.x supports and a single application can include verticles written in multiple languages.
You can think of a verticle as a bit like an actor in the Actor Model.
An application would typically be composed of many verticle instances running in the same Vert.x instance 
at the same time.The different verticle instances communicate with each other by sending messages on the event bus.
```
**3. Vertx 好处**
   ![select](https://github.com/xiaobaojiang/xiaobaojiang.github.io/blob/master/images/vertx.png)
   
# 异步编程模型
1. CallBack Hell
2. Future
3. Reactive(RxJava)
4. Coroutine(协成)
