---
layout: page
permalink: /news/
title: news          # 这个必须留着给系统识别，但我们在下面手动隐藏它
description: 
nav: true
nav_order: 5
display_categories: [work, fun]
horizontal: false
---

<style>
  header.post-header {
    display: none !important;
  }
</style>

<div class="header" style="color: #c9302c; font-size: 1.5rem; font-weight: bold; margin-top: 0px; margin-bottom: 20px; border-bottom: 1px solid #eee; padding-bottom: 8px; letter-spacing: 0.5px;">
  News
</div>

{% include news.liquid %}