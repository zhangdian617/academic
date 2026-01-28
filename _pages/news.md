---
layout: page
permalink: /news/
title: NEWS          # 这个必须留着给系统识别，但我们在下面手动隐藏它
description: 
nav: true
nav_order: 5
display_categories: [work, fun]
horizontal: false
---

<style>

/* (A) 把整个网页背景变成浅灰色 */
  body {
      background-color: #f4f6f8 !important; 
  }

  /* (B) 把内容容器变成“白纸” */
  body > .container {
      background-color: #ffffff !important; 
      max-width: 1150px !important; 
      
      /* 制造立体感的阴影 */
      box-shadow: 0 4px 20px rgba(0, 0, 0, 0.08); 
      
      /* 内部留白 */
      padding: 40px 60px !important; 
      
      /* 外部留白 */
      margin-top: 30px;
      margin-bottom: 60px;
      
      /* 深红条 */
      border-top: 5px solid #c9302c; 
      
      /* 轻微圆角 */
      border-radius: 4px; 
  }

  header.post-header {
    display: none !important;
  }
</style>

<div class="header" style="color: #c9302c; font-size: 2.0rem; font-weight: bold; margin-top: 0px; margin-bottom: 20px; border-bottom: 1px solid #eee; padding-bottom: 8px; letter-spacing: 0.5px;">
  News
</div>

{% include news.liquid %}