---
layout: post
title: "twitter bootstrap"
category: learning
tags: [web]
description: |
  学习bootstrap并进行练习
---

##排版
**排版用嵌套div完成，嵌套div的class遵循container-row-span的原则**

**row内span数字和不能超过12，超过12布局会错乱**
###固定排版
    <div class="row">
      <div class="span4">abc</div>
      <div class="span8">def</div>
    </div>
显示效果--为了能看到显示效果增加了show-grid
<div class="container">
<div class="row show-grid">
<div class="span4">abc</div>
<div class="span8">def</div>
</div>
</div>

<div class="container">
<div class="row show-grid">
<div class="span1">abc</div>
<div class="span1">abc</div>
<div class="span1">abc</div>
<div class="span1">abc</div>
<div class="span1">abc</div>
<div class="span1">abc</div>
<div class="span1">abc</div>
<div class="span1">abc</div>
<div class="span1">abc</div>
<div class="span1">abc</div>
<div class="span1">abc</div>
<div class="span1">abc</div>
</div>

<div class="row show-grid">
<div class="span4">abc</div>
<div class="span8">abc</div>
</div>

<div class="row show-grid">
<div class="span4">abc</div>
<div class="span4">abc</div>
<div class="span4">abc</div>
</div>
</div>
###流动排版
基本原则和固定排版一致就是用container-fluid,row-fluid替代container,row




{% include JB/setup %}




<div class="alert alert-block alert-warn form-inline" style="text-align:center; vertical-align:middle; font-size: 16px; font-weight:300;">To be continue!</div>
