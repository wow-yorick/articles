# markdown语法

[TOC]



~~~lisp
(+ 1 3)
~~~

~~~markdown
```
代码块
```
~~~
- [x] 任务列表
- [ ] 任务
  
  
  
  ~~~markdown
  - [x] 
  - [ ]
  ~~~
- ## 3. 字体{#index}
  
  *斜体* _斜体_ 
  
  **粗体**
  
  ***加粗斜体*** 
  
  ~~删除线~~
  
  ++下划线++
  
  ==背景高亮== 
  
  ~~~
  *斜体*或_斜体_
  **粗体**
  ***加粗斜体***
  ~~删除线~~
  ++下划线++
  ==背景高亮==
  ~~~
- ## 超链接
  
  欢迎阅读[信息](http://www.5zyx.com "什么")
  
  ~~~markdown
  欢迎阅读 [择势勤](https://www.jianshu.com/u/16d77399d3a7 "择势勤")
  ~~~
- ## 参考式
  
  我经常去的几个网站[Google][1] [Leanote][2]
  
  [1]:http://www.google.com	"按时"
  [2]:http://www.leanote.com	"什么"
  
  
  
  ~~~
  我经常去的几个网站[Google][1]、[Leanote][2]。
  
  [1]:http://www.google.com 
  [2]:http://www.leanote.com
  ~~~
- ## 注脚
  
  使用 markdown[^1] 直接转换成html[^2]
  
  [^1]:Markdown
  [^2]: html
- ## 自动链接
  
  <http://www.baidu.com>
  
  ~~~
  <http://www.xxx.com>
  ~~~
- ## 无序列表、有序列表、定义型列表
- ## 无序列表
  
  * 无序1
  + 无序二
	- 无序三
	  
	  ~~~
	  *
	  -
	  +
	  ~~~
- ### 有序列表
  
  1. 什么
  2. 读
  
  ~~~
  1.
  2. 
  ~~~
- ### 定义型列表
  
  定义型列表由名词和解释组成。一行写上定义，紧跟一行写上解释。解释的写法:紧跟一个缩进(Tab)
  
  名词定义
  
  ​	解释
  
  
  
  ```undefined
  轻量级文本标记语言（左侧有一个可见的冒号和四个不可见的空格）
  ```
  
  :    sadfasdf
  
  :    的法撒旦法
- ## 插入图片
  
  ![dsdf](/Users/yudong/Documents/img/2.png)
  
  
  
  
  
  ~~~
  <center>  <!--开始居中对齐-->
  
  ![GitHub set up](http://zh.mweb.im/asset/img/set-up-git.gif "图片Title")
  格式: ![图片Alt](图片地址 "图片Title")
  </center> <!--结束居中对齐-->
  ~~~
- ### 多级引用
  
  
  
  > > saasdsadfdsaf
  > >
  > > > sdf
  > > >
  > > > > sdaf
  
  
  
  ~~~
  > f
  >> f
  >>> s
  ~~~
- ### 行内式代码块
  
  c语言中的函数 `阿斯蒂` 撒旦法
- ### 流程图
  
  
  
  ~~~graph LR
  graph LR
  A-->B
  ~~~
- ### 表格
  
  
  
  | 什么     | 啊       |
  | -------- | -------- |
  | 阿斯蒂   | 阿斯蒂芬 |
  | 阿斯蒂芬 | 撒旦法   |
  | 撒旦法   | 发       |
- ### LaTeX 公式
  
  
  
  $E = M C^2 $
  
  ~~~
  $E = m c^2 $
  $$ 公式 $$
  ~~~
- ### 分割线
  
  
  
  ***
  
  ---
  
  ~~~
  ---
  ***
  ~~~