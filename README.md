# 设计规范

- [Tips](#tips-)
- [Balloon](#balloon-)
- [Pagination](#pagination-)
- [Grid](#grid)
- [Form](#form-)
- [Tab](#tab)
- [Icons](#icons-)
- [Slideshow](#slideshow-)
- [Typo](#typo)

<h2 id="inline_tips">Tips 提示</h2>

### 定义

__Tips（提示）__是指一个小的弹出窗口，用于精确地描述被指向的对象，例如导航、图标、图形、链接、以及任务栏按钮的描述信息。信息提示是渐进展开（Progressive Disclosure）的一种形式，避免总是将描述文本显示在屏幕上。

### 设计理念

设计易于发现的提示，在恰当的位置和时候显示简洁、实用、辅助性的信息。

### 设计规范

__注意：TIPS中不得含有连接或按钮__

![](https://raw.github.com/jumbo/guide/gh-pages/images/guide/tips.jpg)

* 边框： `#C5C5C5 1px `，无投影
* 大小： 高度范围`41px`~`350px`，宽度范围`55px`~`400px` 
* 边框到内容间距：__ `10px`
* 分隔线： `C5C5C5`
* 正文： `#333333 12px Regular`
* 标题或着重标示文字： `strong/#333333/#0066cc/#306db4/#fe9913`
* 辅助文字： `#999999`
* 中文字体： `宋体`
* 英文字体： `Tahoma`
* 正文行距： `24px`
* 箭头与边框距离： 箭头只可出现在距离边框四个直角`10px`处；或边框中心的位置
* 激活方式： 当鼠标划过描述对象时Tips会出现，鼠标移动到描述对象外位置时，Tips消失
* 位置： Tips默认出现在描述对象的下方和右侧。超出状况下JS控制反转

`注：可能根据实际情况调整字体和色值`

* * * 

<h2 id="inline_balloon">Balloon 气球状提示</h2>

### 定义

网页中的“气球状提示( Balloon )”用于提醒用户那些与用户当前活动无关的事件。它是一个小型的弹出窗口，可帮助用户理解那些未知或不太熟悉的、用户界面（UI）上又缺乏直接描述的对象

* Balloon可包含按钮或链接
* Balloon可以被关闭

### 设计规范

#### 高层级(需强调的）balloon——共性

![](https://raw.github.com/jumbo/guide/gh-pages/images/guide/balloon1.png)
![](https://raw.github.com/jumbo/guide/gh-pages/images/guide/balloon2.png)

* 边框： `#0066CC 2px`，有投影
* 大小： 高度范围`41px`~`450px`，宽度范围`55px`~`500px` 
* 边框到内容间距： `10px`
* 正文： `#666666 12px Regular`
* 标题或着重标示文字： `strong/#666666/#0066cc`
* 中文字体： `宋体`
* 英文字体： `Tahoma`
* 正文行距： `20px`
* 箭头与边框距离： 最短处为`10px`
* 控件到正文的距离： `10px`
* 关闭控件： Tahoma的 `&times; 18px`
* 箭头与边框距离： 箭头只可出现在在距离边框四个直角处`10px`的位置。
* 激活方式： 一般为打开页面时默认出现，有时也会点击描述对象时出现。均为点击关闭控件时消失
* 位置： Balloon默认出现在描述对象的上方。仅页面高度小于balloon的高度时，Balloon出现在描述对象下方。不允许出现在描述对象的两侧

#### 低层级balloon——共性

![](https://raw.github.com/jumbo/guide/gh-pages/images/guide/balloon3.png)
![](https://raw.github.com/jumbo/guide/gh-pages/images/guide/balloon4.png)

* 边框： `#0066CC 1px`，无投影
* 大小： 高度范围`41px`~`450px`，宽度范围`55px`~`500px` 
* 边框到内容间距： `10px`
* 正文： `#666666 12px Regular`
* 标题或着重标示文字： `strong/#666666/#0066cc`
* 中文字体： `宋体`
* 英文字体： `Tahoma`
* 正文行距： `20px`
* 箭头与边框距离： 最短处为`10px`
* 控件到正文的距离： `10px`
* 关闭控件： Tahoma的 `&times 18px`
* 箭头与边框距离： 箭头只可出现在在距离边框四个直角处`10px`的位置
* 激活方式： 一般为打开页面时默认出现，有时也会点击描述对象时出现。均为点击关闭控件时消失
* 位置： Balloon默认出现在描述对象的上方。仅页面高度小于balloon的高度时，Balloon出现在描述对象下方。不允许出现在描述对象的两侧

* * * 

<h2 id="inline_pagination">Pagination 分页</h2>

### 通用分页样式

适用范围：各类列表页、搜索结果页、评论模块等

![](https://raw.github.com/jumbo/guide/gh-pages/images/guide/pagination1.png)

### 简版分页样式

适用范围：各类列表模块顶部

![](https://raw.github.com/jumbo/guide/gh-pages/images/guide/pagination2.png)

### 小分页

适用范围：宽度较小、结构较为紧密的模块，比如弹出层等

![](https://raw.github.com/jumbo/guide/gh-pages/images/guide/pagination3.png)

* * * 

<h2 id="inline_grid">Grid</h2>

栅格系统，是以规则的网格阵列来指导和规范网页中的版面布局以及信息分布。
在网页设计中使用栅格系统，可以让网页的信息呈现更加美观易读，更具可用性。而且对于前端开发来说，网页将更加的灵活与规范。

__Ctrip UI2.0栅格系统以60px为基础，共15列，列间距为20px。__

* Content width：1180px
* Column width：60px
* Number of columns：15
* Gutter width：20px

![](https://raw.github.com/jumbo/guide/gh-pages/images/guide/grid1.png)

建议使用的栅格布局：

![](https://raw.github.com/jumbo/guide/gh-pages/images/guide/grid2.png)

* * * 

<h2 id="inline_form">Form 表单</h2>

### 输入框

*  尺寸

    ![](https://raw.github.com/jumbo/guide/gh-pages/images/guide/form1.png)

* 各种状态色值

  * 普通状态 normal

      * 边框 `#bbbbbb`
      * 文字 `#333333`
      * 提示 `#999999`

  * 输入状态 focus

      * 边框 `#5d9de5`

  * 报错 error

      * 边框 `#d80000`
      * 背景 `#fff7d9`

* 内阴影样式

    登录页以及各频道搜索框内的输入框，需添加内阴影

    ![](https://raw.github.com/jumbo/guide/gh-pages/images/guide/form2.png)

    ```css
    border-color: #bbbbbb #dddddd #dddddd #bbbbbb;
    box-shadow: 1px 1px 1px #dddddd inset;
    ```

* 下拉框
    * 默认样式
      下拉框一般情况下都使用系统默认样式

       ![](https://raw.github.com/jumbo/guide/gh-pages/images/guide/form3.png)

        * 高度：`22px`
        * 边框：` #bbbbbb`
    * 自定义样式
      当下拉框的内容使用默认样式无法实现时，允许使用自定义样式

      自定义样式范例：

      ![](https://raw.github.com/jumbo/guide/gh-pages/images/guide/form4.png)

* 单选、复选框

  ![](https://raw.github.com/jumbo/guide/gh-pages/images/guide/form5.png)

* * * 

<h2 id="inline_tab">Tab</h2>

当前选中项使用蓝色文字  `#0066cc`，未选中可点击项使用黑色文字  `#333333`

* 一级tab样例：

  ![](https://raw.github.com/jumbo/guide/gh-pages/images/guide/tab1.png)

  ![](https://raw.github.com/jumbo/guide/gh-pages/images/guide/tab2.png)

* 二级tab样例：

  ![](https://raw.github.com/jumbo/guide/gh-pages/images/guide/tab3.png)

<h2 id="inline_icons">Icons 提示图标</h2>

* 成功 success

  ![](https://raw.github.com/jumbo/guide/gh-pages/images/guide/icon1.png)

* 信息 infomation

  ![](https://raw.github.com/jumbo/guide/gh-pages/images/guide/icon2.png)

* 警告 alert

  ![](https://raw.github.com/jumbo/guide/gh-pages/images/guide/icon3.png)

* 错误 error

 ![](https://raw.github.com/jumbo/guide/gh-pages/images/guide/icon4.png)

* * * 

<h2 id="inline_slideshow">Slideshow 轮播</h2>

* 轮播图片切换圆点

  对于全站各频道首页广告轮播图上的切换圆点进行样式规范，统一圆点的位置，间隔，颜色

    * 位置

      距离广告图的右边距、下边距各为10px

      ![](https://raw.github.com/jumbo/guide/gh-pages/images/guide/slideshow1.png)

    * 间隔 `8px`
    * 色值：边框 `#ffffff 2px` 选中圆点 `#f8cd47` 未选中圆点 `#999999`

* 滚动播放箭头样式
    * 样式
        * Clickable

          ![](https://raw.github.com/jumbo/guide/gh-pages/images/guide/slideshow_control1.png)

          ![](https://raw.github.com/jumbo/guide/gh-pages/images/guide/slideshow_control2.png)

          灰色：`#a7a7a7` 蓝色：`#3d95ec`

        * Hover

          ![](https://raw.github.com/jumbo/guide/gh-pages/images/guide/slideshow_control3.png)

          ![](https://raw.github.com/jumbo/guide/gh-pages/images/guide/slideshow_control4.png)

          橙色：`#ff9c0a`

        * Disable

          ![](https://raw.github.com/jumbo/guide/gh-pages/images/guide/slideshow_control5.png)

          ![](https://raw.github.com/jumbo/guide/gh-pages/images/guide/slideshow_control6.png)

          灰色：`#d5d5d5`

      根据模块权重的不同，clickable状态允许使用灰色或蓝色箭头。

      根据页面整体色调，允许对箭头颜色进行微调。

* * * 

<h2 id="inline_typo">Typo</h2>

* 字体与字号

  ![](https://raw.github.com/jumbo/guide/gh-pages/images/guide/typo1.png)

* 颜色

    * `#cccccc`  SEO区域
    * `#999999`  非重要内容，提示信息，SEO区域
    * `#666666`  次要级别正文
    * `#333333`  正文，标题
    * `#0066cc`  主链接颜色
    * `#77aadd`  辅助链接颜色
    * `#5599dd`  标题，tab
    * `#ff6600`  价格
    * `#bb0000`  警示强调
    * `#10a200`  免费信息预订时间

* 间距和缩进

    * 模块间距

      根据UI 2.0栅格系统规范，因纵向栅格模块间隔为20px，所以横向模块间距要≥20px，规则如下：

        * 以图片或色块为底色的模块之间：间距为20px    纯文字或图文混排的模块之间：间距为30px

          ![](https://raw.github.com/jumbo/guide/gh-pages/images/guide/typo2.png)

    * 模块缩进

      根据模块宽度的不同，模块内部缩进在10～15px之间。对于没有边框或底色的模块一般不使用缩进

      ![](https://raw.github.com/jumbo/guide/gh-pages/images/guide/typo3.png)

    * 文字行距

      ![](https://raw.github.com/jumbo/guide/gh-pages/images/guide/typo4.png)
