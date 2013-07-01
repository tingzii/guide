# 设计规范

## Tips 提示

### 定义

__Tips（提示）__是指一个小的弹出窗口，用于精确地描述被指向的对象，例如导航、图标、图形、链接、以及任务栏按钮的描述信息。信息提示是渐进展开（Progressive Disclosure）的一种形式，避免总是将描述文本显示在屏幕上。

### 设计理念

设计易于发现的提示，在恰当的位置和时候显示简洁、实用、辅助性的信息。

### 设计规范

__注意：TIPS中不得含有连接或按钮__

<img width="575" height="332" src="https://raw.github.com/jumbo/guide/gh-pages/images/guide/tips.jpg">

* __边框：__ `#C5C5C5 1px `，无投影
* __大小：__ 高度范围`41px`~`350px`，宽度范围`55px`~`400px` 
* __边框到内容间距：__ `10px`
* __分隔线：__ `C5C5C5`
* __正文：__ `#333333 12px Regular`
* __标题或着重标示文字：__ `strong/#333333/#0066cc/#306db4/#fe9913`
* __辅助文字：__ `#999999`
* __中文字体：__ `宋体`
* __英文字体：__ `Tahoma`
* __正文行距：__ `24px`
* __箭头与边框距离：__ 箭头只可出现在距离边框四个直角`10px`处；或边框中心的位置
* __激活方式：__ 当鼠标划过描述对象时Tips会出现，鼠标移动到描述对象外位置时，Tips消失
* __位置：__ Tips默认出现在描述对象的下方和右侧。超出状况下JS控制反转

`注：可能根据实际情况调整字体和色值`

### 代码实现 - TODO

## Ballons 气球状提示

### 定义

网页中的“气球状提示( Ballon )”用于提醒用户那些与用户当前活动无关的事件。它是一个小型的弹出窗口，可帮助用户理解那些未知或不太熟悉的、用户界面（UI）上又缺乏直接描述的对象

* Ballon可包含按钮或链接
* Ballon可以被关闭

### 设计规范

#### 高层级(需强调的）ballon——共性

<img align="right" width="424" height="180" src="https://raw.github.com/jumbo/guide/gh-pages/images/guide/balloon1.png">
<img align="right" width="424" height="180" src="https://raw.github.com/jumbo/guide/gh-pages/images/guide/balloon2.png">
* __边框：__ `#0066CC 2px`，有投影
* __大小：__ 高度范围`41px`~`450px`，宽度范围`55px`~`500px` 
* __边框到内容间距：__ `10px`
* __正文：__ `#666666 12px Regular`
* __标题或着重标示文字：__ `strong/#666666/#0066cc`
* __中文字体：__ `宋体`
* __英文字体：__ `Tahoma`
* __正文行距：__ `20px`
* __箭头与边框距离：__ 最短处为`10px`
* __控件到正文的距离：__ `10px`
* __关闭控件：__ Tahoma的 `&times; 18px`
* __箭头与边框距离：__ 箭头只可出现在在距离边框四个直角处`10px`的位置。
* __激活方式：__ 一般为打开页面时默认出现，有时也会点击描述对象时出现。均为点击关闭控件时消失
* __位置：__ Ballon默认出现在描述对象的上方。仅页面高度小于ballon的高度时，Ballon出现在描述对象下方。不允许出现在描述对象的两侧

#### 低层级ballon——共性

<img align="right" width="424" height="180" src="https://raw.github.com/jumbo/guide/gh-pages/images/guide/balloon3.png">
<img align="right" width="424" height="180" src="https://raw.github.com/jumbo/guide/gh-pages/images/guide/balloon4.png">
* __边框：__ `#0066CC 1px`，无投影
* __大小：__ 高度范围`41px`~`450px`，宽度范围`55px`~`500px` 
* __边框到内容间距：__ `10px`
* __正文：__ `#666666 12px Regular`
* __标题或着重标示文字：__ `strong/#666666/#0066cc`
* __中文字体：__ `宋体`
* __英文字体：__ `Tahoma`
* __正文行距：__ `20px`
* __箭头与边框距离：__ 最短处为`10px`
* __控件到正文的距离：__ `10px`
* __关闭控件：__ Tahoma的 `&times 18px`
* __箭头与边框距离：__ 箭头只可出现在在距离边框四个直角处`10px`的位置
* __激活方式：__ 一般为打开页面时默认出现，有时也会点击描述对象时出现。均为点击关闭控件时消失
* __位置：__ Ballon默认出现在描述对象的上方。仅页面高度小于ballon的高度时，Ballon出现在描述对象下方。不允许出现在描述对象的两侧

### 代码实现 - TODO

