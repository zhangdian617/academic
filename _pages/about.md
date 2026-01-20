---
layout: about
title: about
permalink: /
subtitle: 

# 禁用默认 Profile
profile: 
  enabled: false 

selected_papers: true
social: false 

announcements:
  enabled: true
  scrollable: true
  limit: 5

latest_posts:
  enabled: false 
---

<!-- 1. 自定义样式区域 -->
<style>
    /* --- 1. 隐藏默认标题 */
    header.post-header {
        display: none !important;
    }

    
    /* (A) 把整个网页背景变成浅灰色 */
    body {
        background-color: #f4f6f8 !important; /* 一种高级的浅灰 */
    }

    /* (B) 把内容容器变成“白纸” */
    body > .container {
        background-color: #ffffff !important; /* 纯白背景 */
        max-width: 1150px !important; /* 限制最大宽度，模仿邹老师的窄版设计 */
        
        /* 制造立体感的阴影 */
        box-shadow: 0 4px 20px rgba(0, 0, 0, 0.08); 
        
        /* 内部留白，文字不贴边 */
        padding: 40px 60px !important; 
        
        /* 外部留白，让它浮在中间 */
        margin-top: 30px;
        margin-bottom: 60px;
        
        /* 深红条 */
        border-top: 5px solid #c9302c; 
        
        /* 轻微圆角 */
        border-radius: 4px; 
    }

    .header {
        color: #c9302c;
        font-size: 1.5rem;
        font-weight: bold;
        margin-top: 40px;
        margin-bottom: 20px;
        border-bottom: 1px solid #eee;
        padding-bottom: 8px;
        letter-spacing: 0.5px; /* 字间距稍微宽一点 */
    }

    /* --- 4. 个人信息文字优化 --- */
    .info-text p {
        margin-bottom: 6px;
        font-size: 0.95rem;
    }
    .info-text a {
        color: #0056b3;
        text-decoration: none;
    }
    .info-text a:hover {
        text-decoration: underline;
    }

    /* --- 5. 手机端适配 (手机屏幕窄，去掉两侧留白) --- */
    @media (max-width: 768px) {
        body > .container {
            width: 100% !important;
            max-width: 100% !important;
            margin: 0 !important;
            padding: 20px !important;
            box-shadow: none !important; /* 手机上去掉阴影，铺满屏幕 */
            border-top: none; /* 手机上也许可以去掉红条 */
        }
    }
</style>

<!-- 2. 核心布局：头像 + 个人信息 -->
<!-- 这里开始 -->
<div class="row mb-5">
    
    <!-- 左侧头像 (占 3/12 宽度) -->
    <div class="col-sm-3 text-center">
        <img src="{{ '/assets/img/test1.jpg' | relative_url }}" class="img-fluid rounded" style="max-width: 100%; border: 1px solid #ddd; padding: 3px;" alt="Profile Picture">
    </div>

    <!-- 右侧信息 (占 9/12 宽度) -->
    <div class="col-sm-9 info-text">
        <!-- 名字与职称 -->
        <h2 style="margin-top: 0; font-weight: bold; color: #333; font-family: 'Times New Roman', serif;">
            Dian Zhang (张滇)
        </h2>
        <p style="color: #555; margin-bottom: 10px; font-weight: 500;">
            Associate Professor / Ph.D Supervisor
        </p>
        
        <!-- 核心信息区域 -->
        <div style="font-size: 0.95rem; line-height: 1.6;">
            
            <!-- 学院/学校 -->
            <div class="mb-1">
                <span style="font-weight: bold;">Lingnan University</span><br>
                <a href="#" target="_blank" style="color: #0056b3;">College of Computer Science (Example)</a>
            </div>

            <!-- 地址 -->
            <div class="mb-1">
                <i class="fas fa-map-marker-alt fa-fw" style="color: #444;"></i>
                Room G09/9, Lingnan Hub, Lingnan University, Hong Kong
            </div>
            
            <!-- 电话 + 邮箱 -->
            <div class="mb-1">
                <span style="margin-right: 25px;">
                    <i class="fas fa-phone fa-fw" style="color: #444;"></i> (0755) 8983-7853
                </span>
                <span>
                    <i class="fas fa-envelope fa-fw" style="color: #444;"></i> 
                    <a href="mailto:zhangdian@ln.edu.hk">zhangdian@ln.edu.hk</a>
                </span>
            </div>

            <!-- 外部链接 -->
            <div class="mt-2">
                <i class="fas fa-globe fa-fw" style="color: #444;"></i> 
                [<a href="https://scholar.google.com" target="_blank">Google Scholar</a>] 
                [<a href="#" target="_blank">DBLP</a>] 
                [<a href="https://github.com/zhangdian617" target="_blank">GitHub</a>]
                [<a href="#" target="_blank">中文主页</a>]
            </div>
        </div> <!-- 关闭 核心信息区域 div -->
    </div> <!-- 关闭 右侧信息 col-sm-9 -->

</div>


<!-- 3. 个人简介 (BIOGRAPHY) -->
<div class="header">BIOGRAPHY</div>

<div class="text-justify">
    <p>
        I have long been engaged in the fields of mobile computing, smart healthcare and data analytics, having published approximately 60 papers in top international conferences and journals. The majority of these papers are first-authored by myself or graduate students under my supervision. The total amount of research funding (PI/CI) exceeds 10 Million Yuan. 
    </p>
    <p>
        As one of the earliest researchers to pioneer device-free localization and behavior recognition technologies, I designed novel algorithms for device-free object positioning and behavioral sensing, establishing new research directions in this field. My work has been recognized with prestigious awards, including: 
        <b>2019 Ministry of Education Natural Science Second Prize</b> (教育部自然科学二等奖), 
        <b>2022 Shenzhen Natural Science Award First Prize</b> (深圳市自然科学一等奖), 
        and <b>2019 Pacific Insurance Company Academic Achievement Award</b>. 
    </p>
    <p>
        My work in smart dental (healthcare) received <b>2024 Chinese Stomatological Association Annual Conference First Prize</b> (corresponding author)(中华口腔医学会年会一等壁报), and <b>International Association for Dental Research Southeast Asian Division (IADR-SEA) Research award</b> (国际牙科研究协会亚太区研究贡献奖). Due to the contribution in smart dental, I was appointed Honorary Professor by the Faculty of Dentistry at the University of Hong Kong (ranked 2nd globally in Dentistry by QS World University Rankings).
    </p>
</div>

<!-- 4. 新闻动态 (News) -->
<div class="header">News</div>

<!-- 这里会自动加载 _news 文件夹里的内容 -->