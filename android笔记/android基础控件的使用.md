[TOC]

#前言：熟悉基础控件的使用

* 基本控件的一些属性使用，切合到源码，原理分析。
* 界面编程方面的知识 颜色的运用
* 常用属性,或特殊运用方法的深刻理解

***


#基础控件使用
##TextView 

HTML字符的输入
mTextView.setText(Html.formHtml("<html代码>"))
其原理：

``` java
Spannable s = new SapnableString(mTextView.getText());
s.setSpan(new BackgroundColor(Color.RED) ,0,3,0); <最后一个是flag>
```

TextView

  lineSpacingMultiplier 行高属性

##ImageView

ImageView的几种方式

ImageButton 默认会使用背景
于是就要使用透明背景将其覆盖： 八位十六进制的颜色 透明  红 绿 蓝
##Button

***
#共有属性使用
weight 的使用

 表示剩余区域 一般用height 或 width 为 0 ，然后使用 weight
