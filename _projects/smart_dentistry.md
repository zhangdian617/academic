---
layout: page
title: AI-Driven Digital Dentistry
description: Next-Gen AI Framework for 3D Reconstruction, Orthodontics, and Chairside Manufacturing.
img: assets/img/smart_dentistry/preview.jpg
importance: 1
category: Smart Healthcare
related_publications: false 
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

</style>

<div class="row justify-content-center mb-4">
    <div class="col-md-10 text-center">
        <h3 style="font-weight: 300; color: #555;">Revolutionizing Oral Healthcare with Artificial Intelligence</h3>
        <p class="lead" style="font-size: 1.1rem; color: #777;">
            From multi-modal data fusion to chairside manufacturing, we are building a complete closed-loop digital ecosystem.
        </p>
    </div>
</div>

<hr>

<h3 class="mt-4 mb-3" style="border-left: 4px solid #c9302c; padding-left: 10px;">1. Multi-modal Data Fusion & AI Processing</h3>

<!-- 第一行：两张图片  -->
<div class="row mb-4 align-items-center">
    <!-- 左图：CBCT -->
    <div class="col-sm-6">
        {% include figure.liquid loading="eager" path="assets/img/smart_dentistry/2.jpg" title="Input: CBCT Data" class="img-fluid rounded z-depth-1" %}
        <div class="caption text-center mt-2">Input 1: CBCT Data</div>
    </div>
    
    <!-- 右图：Oral Scan -->
    <div class="col-sm-6">
        {% include figure.liquid loading="eager" path="assets/img/smart_dentistry/3.jpg" title="Input: Oral Scan" class="img-fluid rounded z-depth-1" %}
        <div class="caption text-center mt-2">Input 2: Oral Scan Data</div>
    </div>
</div>

<!-- 第二行：三个视频 (各占 33.3% 宽度) -->
<div class="row">
    <!-- 视频 A -->
    <div class="col-sm-4">
        <div class="rounded z-depth-1" style="overflow: hidden; line-height: 0;">
            <video autoplay loop muted playsinline style="width: 100%; height: auto;">
                <source src="{{ '/assets/video/smart_dentistry/v1.mp4' | relative_url }}" type="video/mp4">
            </video>
        </div>
        <div class="caption mt-2">Process A: AI Segmentation</div>
    </div>

    <!-- 视频 B -->
    <div class="col-sm-4">
        <div class="rounded z-depth-1" style="overflow: hidden; line-height: 0;">
            <video autoplay loop muted playsinline style="width: 100%; height: auto;">
                <source src="{{ '/assets/video/smart_dentistry/v2.mp4' | relative_url }}" type="video/mp4">
            </video>
        </div>
        <div class="caption mt-2">Process B: Original Scan Model</div>
    </div>

    <!-- 视频 Result (原本被截断的那个) -->
    <div class="col-sm-4">
        <!-- 去掉了强制的高度限制，让它自然撑开 -->
        <div class="rounded z-depth-1" style="overflow: hidden; line-height: 0; background: #000;">
            <video autoplay loop muted playsinline style="width: 100%; height: auto;">
                <source src="{{ '/assets/video/smart_dentistry/v3.mp4' | relative_url }}" type="video/mp4">
            </video>
        </div>
        <div class="caption mt-2 font-weight-bold">Result: Multi-modal Fusion</div>
    </div>
</div>

<hr class="my-5">

<h3 class="mt-4 mb-3" style="border-left: 4px solid #c9302c; padding-left: 10px;">2. Teeth Alignment (TAPoseNet)</h3>

<div class="row mb-3">
    <div class="col-md-12">
        <p>
            <strong>TAPoseNet (MICCAI 2024)</strong>: Teeth Alignment based on Pose estimation via multi-scale Graph Convolutional Network.
        </p>
    </div>
</div>

<div class="row justify-content-center p-3 rounded" style="background-color: #1e1e1e;">
    <div class="col-md-10">
        <div class="rounded z-depth-2" style="overflow: hidden;">
            <video controls style="width: 100%;">
                <source src="{{ '/assets/video/smart_dentistry/v4.mp4' | relative_url }}" type="video/mp4">
            </video>
        </div>
        <p class="text-center mt-2 text-white-50" style="font-size: 0.9rem;">
            Visualization of the Alignment Process
        </p>
    </div>
</div>

<hr class="my-5">

<h3 class="mt-4 mb-3" style="border-left: 4px solid #c9302c; padding-left: 10px;">3. Chairside Clear Aligner Printing</h3>

<div class="row align-items-center">
    <div class="col-sm-4">
        {% include figure.liquid path="assets/img/smart_dentistry/8.jpg" title="Comparison" class="img-fluid rounded" %}
        <div class="caption">Direct Printing vs. Thermoforming</div>
    </div>

    <div class="col-sm-4">
        <div class="rounded z-depth-1 border" style="overflow: hidden; line-height: 0;">
            <video autoplay loop muted playsinline style="width: 100%; height: auto;">
                <source src="{{ '/assets/video/smart_dentistry/v5.mp4' | relative_url }}" type="video/mp4">
            </video>
        </div>
        <div class="caption">High-speed Chairside Printing</div>
    </div>

    <div class="col-sm-4">
        {% include figure.liquid path="assets/img/smart_dentistry/14.jpg" title="Final Product" class="img-fluid rounded" %}
        <div class="caption">Directly Printed Aligners</div>
    </div>
</div>

<hr class="my-5">

<h3 class="mt-4 mb-3">Reference</h3>

<div class="publications">
  {% bibliography --query @*[title~=TAPoseNet] %}
  {% bibliography --query @*[title~=MVDC] %}
</div>
