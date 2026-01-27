---
layout: page
permalink: /publications/
title: PUBLICATIONS
description: 
nav: true
nav_order: 2
---

<!-- _pages/publications.md -->

<!-- 样式修正补丁 -->
<style>
/* 1. 列表题目加粗 */
.bibliography .title {
    font-weight: bold !important;
    color: #000 !important;
}

/* 2. 作者名字修正：去下划线 + 加粗 */
.bibliography em {
    font-style: normal !important;      
    font-weight: 900 !important;        
    text-decoration: none !important;   
    border-bottom: none !important;     
    color: #000 !important;             
}
/* 兼容性补丁 */
.bibliography b, .bibliography strong {
    font-weight: 900 !important;
    text-decoration: none !important;
}

/* 3. 期刊名称斜体 */
.bibliography .periodical {
    font-style: italic !important; 
}

</style>

<!-- Bibsearch Feature -->

{% include bib_search.liquid %}

<div class="publications">

{% bibliography %}

</div>
