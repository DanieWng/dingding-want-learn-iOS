# 1. 画面点击后的事件响应

在智能机时代用到最多的体验方式是触摸，那么第一个项目的主题就是探索当手指触摸了屏幕之后发生了什么？

当然这里只初步了解点击手势(click gesture)， 即点击按钮后的事件响应机制。像其他的滑动，拖动，长按等再之后的过程中慢慢了解。

### 创建一个空的项目

1. 打开Xcode
2. 点击 - ‘新建项目’
3. 点击 - ‘iOS-Application-Single View App’
4. 修改 - Product Name, Organization Name, Organization Identifier

### 实现

![](http://samvlu.com/images/2015-08-04-tap-counter.gif)

1. 点击**Tap**按钮，文本数字数值递加
2. 点击**Reset**按钮，文本数字数值归零

#### 练习内容
* 构建**Label**和**Button**控件UI接口
* 使用函数连接Button按钮，作为点击事件响应方法
* 学会使用**NSNumberFormatter**类
* 学会Swift语言特性 - **Unwrapping Optionals**（可选变量）的声明，访问
* 构建一个自定义导航条(Navigation Bar)

### 参考
1. [Beginner Xcode and Swift - Learn to make simple game](https://www.youtube.com/watch?v=pTdI7uVbiBg)
2. [100 Days of Swift - samvlu.com](http://samvlu.com/)