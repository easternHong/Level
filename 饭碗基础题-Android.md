### 动态权限适配方案，权限组的概念

### 动态布局

### SP是进程同步吗，有什么方法做到同步？

### 介绍下SurfaceView(阿里，腾讯，大疆)

### BroadcastReceiver,LocalBroadcastReceiver区别,动态广播，静态广播。

### Activity栈

### Service的生命周期

### ListView图片错乱的原理和解决方案

### ListView RecycleView的区别，性能

### Bundle机制

### Handler机制，更多细节，线程如何创建，退出消息循环，Looper怎么启动
```
   关键：nativePoll()阻塞。
   enqueue方法的实现。比如sendMessage,postDelay,消息入列后，顺序是怎么样的。
 ```

### 事件传递机制

### 多线程，AsyncTask设计缺陷。
1.低版本的AT线程池大小设置成了128，高版本设置成CPU_COUNT*2+1
2.容易内存泄漏，结果是post.


### 计算view的嵌套层级

### Intent-filter
