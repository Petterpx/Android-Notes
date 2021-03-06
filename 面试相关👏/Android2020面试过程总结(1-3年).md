# Android面试过程总结(1-3年)

一个 Android 菜瓜的面试之旅，希望对大家有所帮助。

## 一些叨叨

老是听说Android端凉了，寒冬如何如何，老弟觉得并不是，只是饱和了，市场对一个Android开发工程师的要求更加严格，不再是普通的螺丝钉。凭借大多数人的努力程度，那用得着拼其他东西。

面试造🚀?

对也不对，有人曾目睹火箭全貌并加以口述，有人却未曾到达这片领域。面向深度开发工程师与面向Api调用师，差距很小也很大。

`因为热爱，所以才有了一系列开始。`

## 背景

普通专科，毕业 `3` 个月，自考本科湘潭大学，预计2021年结束。

在上家公司去年开始实习并转正，担任`Android端独立开发`，当然做的事也比较多。当过一些小项目的负责人，也调研一些业界常见的方案，比如双因子登录，直播全流程，开发人力成本模型等等。

## 抬头看天

在老东家(项目型公司)呆了一年后，开始逐渐规划一些方向，比如未来3年要达到的高度。于是，我本次的目标是：

**Toc、产品、有技术深度**的公司

## 低头看地

**学历，算法**

前者是个硬伤，也就注定当前这个阶段我是肯定拿不到大厂的面试资格(除非本科自考结束，当然这也只是提高可能性，B数有)；

后者也挺伤，不过Android面试基础算法应该问题不大(`后面被打脸了`)，不过也得花点时间再刷题；

目前相比其他`同阶段`开发者优势劣势在哪里，相比`2-3`年经验的开发者呢，有什么闪光点可以使我超越这帮人呢？

## 地点

`北京`



## 1-3年中小公司常见题(个人总结)

主要还是根据你简历去问，以下主要做一个简单总结：

### java

- gc回收机制
- 多线程，synchronized 与 volatile
- 类加载相关
- hashmap原理，arraylist等等
- java内存区域
- 静态代理与动态代理区别

### Android

- 性能优化，内存泄漏治理，启动优化，包体积优化
- 四大组件(不涉及原理)，是的，依然有公司问，基础很简单，重要是细节
- 进程间通信方式，及部分原理
- 事件分发机制与事件冲突处理
- 热修复与相应第三方实现原理(如tinker)
- handler
- view流程(涉及相应方法内部源码)
- Activity,windows,view关系
- 组件化与模块化

### 三方库

- Retrofit与Okhttp
- Glide

### JetPack

- lifecycle- 原理及为什么要存在它的背景
- ViewModel与LiveData

### Kotlin

- 协程与其他第三方线程框架区别
- kotlin和java你认为的不同
- 相应的内联函数解释一下

### 网络协议

- tcp/ip,http
- 签名与证书

### 设计模式

- 单例
- 代理
- 其他的基本遇到的很少，不过设计模式，日常用的东西

### 算法类

- 二分
- 快排
- 二叉树
- 链表

## 一些面过的公司

### 常青藤爸爸-卒

- 电面 
  - 聊做过的项目
  - 为什么要辞职
  - 为什么要选用组件化
  - 讲一下JetPack部分组件内部实现原理
  - ...
- 二面
  - 个人简介
  - 聊项目组件化，画一下你的框架图，讲一下具体注意事项
  - 说说MVP和MVVM
  - 手写 算法-二分查找

> 原因: 二分查找没写出来，对你没有看错，真的给没写出来，当场差点给老弟哭了。

---

### MetaApp-卒

- 笔试题
  - 大数相加。(禁止使用bigxxx,String长度可能超过long)
  - 两个String字符串除重，确保顺序不变
  - 上述的解法，算法复杂度是多少，有没有达到O(n),没有请实现一个？

> 原因：大数相加写的很失败。

---



## 阶段小总结

老弟算法差到离谱，于是痛定沉思，刷刷算法题，真的是丢人，排序算法，二叉树等等。



---

### 新氧科技-卒

- 一面
  - 聊项目
  - 聊组件化，为什么要用组件化，背景，组件到的依赖问题
  - 聊聊JetPack
  - 项目中用过哪些性能优化说一下？
  - 说一下你是如何做包大小治理的
  - 说一下你的性能优化具体做了啥？
  - 说说SparseArray和HashMap区别，[内部实现]()？
  - 说说为什么CoordLayout为啥比RelayoutLayout效率高，内部实现?
  - 当LinearLayout和CoordLayout相同情况下，优先使用谁，为什么？
  - ...
- 二面
  - 聊聊你在上家公司做了什么
  - 聊聊你为什么要辞职
  - 聊聊你的项目
  - 说一下你知道的基本数据结构
  - 说一下常见排序算法
  - 说一下快速排序的原理
  - 你还有什么想问的吗
  - 

> 原因：技术VP觉得工作年限不足，可能是安慰吧。

---

### 未来花朵-婉拒

- 一面
  - 讲讲你的项目
  - 说一下你是如何做包大小治理的
  - 讲一下你对Handler的理解
  - 讲一下view绘制流程
- 二面
  - 讲讲你再上家公司干了什么
  - 讲讲你为什么要辞职
  - 聊聊你的项目
  - 对直播一些问题的解释
  - 讲讲kotlin和协程

> 原因：是一家创业的小公司，在二面中发现面试官技术深度欠缺，与我职业规划有点差异。

---

### 7k7k-婉拒

- 一面
  - 讲讲Android四大组件
  - 说一下编译版本，最低版本，最高版本的区别
  - 说一下Android各版本差异
  - 说一下服务
  - ...
- 二面
  - Java基础考察主要
  - Java多线程相关
  - 两个栈实现队列
  - 二叉树的遍历方式
  - 一个8个石头，一个天平称重，其中一个石头较重，求最快几步(穷举)

> 原因：面试得还不错，同样，这家也是独立开发，他们的擅长是做游戏，于是婉言谢辞。

---

### 彬彬有礼-卒

- 一面
  - 讲讲你负责的项目
  - 说说Android事件分发机制，及dispatchEvent方法内部做了什么？
  - 说一下Retrofit,和Okhttp的区别
  - 说一下glide如何加载指定个数此gif图
  - 说一下内存泄漏常见的场景，及你如何处理一般
- 二面
  - 讲讲为什么要离职
  - 说一下Flutter？
  - 你都了解哪些设计模式，讲一下
  - 。。。

> 原因：应该是音视频不怎么了解导致，这家需要音视频比较了解的小伙伴。

---

### 下厨房-头口offer

- 一面
  - 说一些Activity启动模式及应用场景
  - 说一些Fragment生命周期，及什么时候Fragment.getContext()不为null
  - 说一下Activity与Fragment传值的方法
  - 说一下Java内存区域
  - 说一下GC回收机制
  - 如何保证重复添加同一个Fragment对象时，不会报错
  - 说一下事件分发的流程，及给你一个场景，如何去处理事件冲突
  - 说一下ViewModel和Lifecycle的原理
  - 说一下Retrofit和OkHttp有什么不同
  - 手写归并排序或者快排
  - 计算一个数的最大公约数，求最优算法
  - 如果有埋点需求，这个系统你如何设计，首先应该考虑什么？
  - ...
- 
  
- 二面
  - 忘了都有哪些问题，记得是一个ios面我
- Hr面(电面)

> 原因：一面面试官气场强大，老弟有点紧张，有些问题答得吞吞吐吐，自评60分，二面还不错。最终拿了口头offer,这是意想不到的，一般当天不给结果，我都认为已经结束。

---

## 阶段小总结

老弟对JVM基础了解还差点，简单点来说，背的不熟练，比如Java内存区域这些基础东西，需要看看。



---

### 一下科技-卒(hc满了)

- 一面
  - 讲一下热修复的原理
  - 说一下Java的内存模型及Gc的回收机制
  - 谈一下你项目中用到的IM
  - 简述一下 一个流式布局整体的写法，比如onMeasure和onLayout中做了什么
  - 说一下xml中的布局如何转化为代码
  - 说一下ArrayList和LinkeList区别及实现原理
  - 说一下换肤的原理，讲一下如何动态配置换肤的资源包
  - 说一下你做过的内存优化有哪些？
  - 说一下包大小治理方面你做了什么？
  - ...
- 二面
  - 说一下你认为的组件化与模块化的不同？
  - 说一下TCP三次握手
  - 除了Retrofit，还用过其他网络框架吗，说一下区别
  - 看过OkHttp源码吗，说一下原理
  - 讲一下你对Handler的理解，不要涉及源码
  - 说一下音视频相关的，比如直播的流程
  - 说一下你了解的设计模式
  - ...
- 三面(Hr)
  - 说一下你为什么要离职
  - 谈谈一些想法
  - 以一个非技术角度给我讲一下冒泡排序
  - 说一下TCP三次握手的原因是什么？
  - 说一下你对二叉树掌握多少
  - 说一下常用的排序算法及复杂度和原理
- 四面(交叉面)电面
  - 谈谈你做过的项目
  - 说一下你做过的性能优化有哪些
  - ...
  - 你还有什么要问的吗

> 原因：1，2面聊得都不错，能看出来技术深度不错，3面Hr一上来就问三次握手，老弟有点吃惊，看得出来这个HR有点意思。总体氛围也不错，4面结束，面试官说成了，等人事电话，最后等来了HC满了，也就意思是你被当备胎了。

---

### 壳壳互联-卒

- 一面

  - 稀奇古怪聊了很多

  - 如果让你采用Linux开发，你会同意吗？

  - 最后选答题-app随机拿的：

    1. 知乎App的会员页设计你会考虑什么，都有哪些view,需要注意什么？

    2. 知乎App的我的-上半部分卡片栏你会如何设计？

    3. 如果让你设计一款知乎App,它的架构你如何选择？

       上述问题有10，15，20分钟，选择一个开始作答。

       选了3，组件化结构，最后结合知乎画了一个粗略的框架图

> 总结：面试官人不错，注重发散性思维，看着你自己的想法，如果不了解某个原理，就讲自己的看法，无关对错。

### 乐我无限-卒

- 一面
  - 具体忘了，聊了1个小时

### 硬核聚视-卒

- 一面面试官不讲武德，吊的没法了，你说什么，都说你不对，你问他原因吧，就说你自己回去找;
- 问我为啥选择移动开发，我说开始是因为热爱，来了一句，你和没说有啥区别,硬忍着面完了；
- 一顿c++的问，我是移动开发，好家伙，我是面错岗位了吗？

> 补充，一面是高级面我，二面是loader面，二面感觉很好，现在知道为啥一面当不了loader了？30多了还不讲武德，还是算了吧，怪我太菜。

### 莱特摩比-卒

- 一面
  - 了解过蓝牙吗，你认为它属于四大组件中那一个
  - 使用ping命令如何计算当前已连接wifi下有多少个设备，如何获取？
  - 其他问题忘了，都很简单
- 二面
  - 整体对面试官印象并不是很好

> 总结：这是一家创业公司(996)，是做游戏+app工具，技术栈并不深厚，二面loader没有平易近人的那种感觉，慎重吧

### 奇天乐地-拒

> 怎么说呢，不讲武德，虽然说做sdk开发，典型的套壳app,技术提升毫无帮助。
>
> 试用7天，无工资，如果通过就包含工资，试用期三个月，第一个月不上一金。
>
> 就这条约，招两个人，原因几何呢，心里没点数了，面试官还透漏老板脾气不好，好家伙，这种公司去了完全是放弃自己，看不到任何技术发展。



### 美兰德-拒

- 笔试

  先笔试题4张，Java基础+Android基础

- 一面

  - 技术问题聊得很少，并不适合

## 阶段小总结

也是瞎投简历了，有些跑过去浪费了彼此时间，这点得给自己扇一巴掌。



### 章鱼科技-卒

- 一面

  面试官应该Android新手，聊问题时，小小的眼睛大大的疑惑

- 二面

  - 说一下Http和Tcpip
  - Tcp为什么要三次握手，如何保证握手后就一定没问题
  - 给你两个链表节点，判断这两个链表是否相交
  - 给你一个数组，反序返回出来

> 总结：做智能硬件的公司，其他没什么感受

### 少年得道-70%卒

- 一面

  - 说一下项目中遇到的问题，你怎么解决
  - 说说gc回收机制，怎么回收的流程
  - 说一下app启动流程
  - 说一下内存泄漏的原因和场景
  - 说一下你都做过的内存优化
  - 说一下你怎么做启动优化的
  - 说一下activity,winodws，view三者之间关系
  - 说一下activity转屏后的生命周期变化，及如何避免生命周期改变
  - 说一下你了解的插件化，谈一下为什么要有插件化，需要解决那些技术问题
  - 说一下tinker内部怎么实现
  - 说一下hashMap实现原理
  - 了解过ConcurrentHashMap,说一下原理

  面试官很善谈，对于一个问题，如果你不了解原理，会让你自己想象如何去设计这样的一个组件，发散性思维

> 总结：一家做K12教育的公司，氛围不错，一面中有些原理没答的太好，比如tinker和插件化相关。



### iRigel-70%卒

- 视频面

  引言：我是看你博客过来的，你博客的你还记住多少，我就随便问了哈

  - 你最近看了setContentView源码，你能讲讲吗
  - 说一下你了解的事件分发机制？
  - 我看你面试记录里没写出二分查找，现在也实现了，那你能用非计算机语言描述二分查找吗？
  - 你说一下 你对于 O(logn) 复杂度的理解？
  - 其他问题没记住。。。

> 总结：面试官非常好，注重解决问题的思维能力。











