---
title: RNN算法综述
separator: <!--s-->
verticalSeparator: <!--v-->
theme: simple
highlightTheme: github
css: custom.css
revealOptions:
    transition: 'slide'
    transitionSpeed: fast
    center: false
    slideNumber: "c/t"
    width: 1000
---

<div class="middle center">
<div style="width: 100%">

<img src="assets/bjtu_logo.PNG" alt="RNN Overview" style="width: 500px;"/>

# RNN算法综述

<hr/>

22231301 杨龙澧

计科2206

<div style="text-align: right; font-size: 24pt;">
<div style="width: 90%">
2024.10.4
</div>
</div>

</div>
</div>

<!--v-->
<div style="width: 100%">

# 目录

<hr class="blue-line">

1. 定义概念 
2. 算法介绍 
3. 算法比较
4. 应用实例
5. 学习心得
5. 参考文献

</div>

<!--s-->

<div class="middle center">
<div style="width: 100%">

# Part.1 什么是RNN

</div>
</div>
</section>

<!--v-->

## RNN诞生历史


<hr/>

<!--v-->

## 什么是RNN？
循环神经网络（Recurrent Neural Network, RNN）是一种深度学习模型，专门用于处理序列数据，如时间序列、自然语言或任何形式的有序数据，它在处理序列数据时具有独特的优势。

RNN的**核心特点**是其<mark>循环结构</mark>，这使得网络能够在每个时间步长中传递和更新状态信息。

<div class="three-line">

|表头 a|表头 b|表头 c|
|:--:|:--:|:--:|
|这是一个|一些内容|...|
|三线表|...|...|

</div>

|表头 a|表头 b|表头 c|
|:--:|:--:|:--:|
|这是一个|一些内容|...|
|普通表格|...|...|

<!--s-->

<div class="middle center">
<div style="width: 100%">

# Part.2 RNN算法概览

</div>
</div>
</section>
<!--v-->

## 诞生历史

<div class="three-line">

|表头 a|表头 b|表头 c|
|:--:|:--:|:--:|
|这是一个|一些内容|...|
|三线表|...|...|

</div>

|表头 a|表头 b|表头 c|
|:--:|:--:|:--:|
|这是一个|一些内容|...|
|普通表格|...|...|

<!--s-->

## 多列布局

<div class="mul-cols">
<div class="col">

第一列

- list
- list

</div> <!--这是第一列结束-->

<div class="col">

第二列

```python
class MyClass:
    def __init__(self, ...):
        ...
    def method(self, ...):
        ...
```

</div> <!--这是第二列结束-->
</div> <!--这是第一组多列结束-->

<div class="mul-cols">
<div class="col">

第一列

- list
- list

</div>
<div class="col">

第二列

1. list 
2. list 
    - list

</div>
<div class="col">

第三列

```python
class MyClass:
    def __init__(self, ...):
        ...
    def method(self, ...):
        ...
```

</div>
</div>

<!--v-->

## 标题

<div class="three-line">

|表头 a|表头 b|表头 c|
|:--:|:--:|:--:|
|这是一个|一些内容|...|
|三线表|...|...|

</div>

|表头 a|表头 b|表头 c|
|:--:|:--:|:--:|
|这是一个|一些内容|...|
|普通表格|...|...|

<!--s-->

<div class="middle center">
<div style="width: 100%">

# Part.3 实现流程

一些 markdown

</div>
</div>

<!--s-->

<div class="middle center">
<div style="width: 100%">

# Part.4 应用实例

一些 markdown

</div>
</div>

<!--s-->

<div class="middle center">
<div style="width: 100%">

# Part.5 算法比较

一些 markdown

</div>
</div>

<!--s-->

<div class="middle center">
<div style="width: 100%">

# Part.6 学习心得

一些 markdown

</div>
</div>

<!--s-->

<div class="middle center">
<div style="width: 100%">

# 参考文献

一些 markdown

</div>
</div>
