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

    /* 研究领域样式 */
    .research-topics {
        display: flex;
        flex-wrap: wrap;
        gap: 1rem;
        margin-top: 1rem;
    }

    .topic-tag {
        background-color: #e3f2fd;
        color: #2c3e50;
        padding: 0.5rem 1rem;
        border-radius: 20px;
        font-size: 0.9rem;
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
        <img src="{{ '/assets/img/test2.png' | relative_url }}" class="img-fluid rounded" style="max-width: 100%; border: 1px solid #ddd; padding: 3px;" alt="Profile Picture">
    </div>

    <!-- 右侧信息 (占 9/12 宽度) -->
    <div class="col-sm-9 info-text">
        <!-- 名字与职称 -->
        <h2 style="margin-top: 0; font-weight: bold; color: #333; font-family: 'Times New Roman', serif;">
            Dian Zhang
        </h2>
        <p style="color: #111; margin-bottom: 10px; font-weight: 500;">
            <b>Associate Professor, Ph.D supervisor</b>
        </p>
        <p style="color: #555; margin-bottom: 10px; font-weight: 500;">
            Person-in-Charge, <a href="https://www.ln.edu.hk/sds/dids" target="_blank">Division of Industrial Data Science</a>
        </p>
        <p style="color: #555; margin-bottom: 10px; font-weight: 500;">
            Associate Dean, <a href="https://www.ln.edu.hk/sds" target="_blank">Sochool of Data Science</a>, <a href="https://www.ln.edu.hk" target="_blank">Lingnan University</a>
        </p>
        
        <!-- 核心信息区域 -->
        <div style="font-size: 0.95rem; line-height: 1.6;">

            <!-- 地址 -->
            <div class="mb-1">
                <i class="fas fa-map-marker-alt fa-fw" style="color: #444;"></i>
                Room G09/9, Lingnan Hub, Lingnan University, Hong Kong
            </div>
            
            <!-- 电话 + 邮箱 -->
            <div class="mb-1">
                <span style="margin-right: 25px;">
                    <i class="fas fa-phone fa-fw" style="color: #444;"></i> +86 13500050657
                </span>
                <span>
                    <i class="fas fa-envelope fa-fw" style="color: #444;"></i> 
                    <a href="mailto:zhangdian@ln.edu.hk">zhangdian@ln.edu.hk</a>
                </span>
            </div>

            <!-- 外部链接 -->
            <div class="mt-2">
                <i class="fas fa-globe fa-fw" style="color: #444;"></i> 
                [<a href="https://scholar.google.com/citations?user=tiE0IDMAAAAJ&hl=zh-CN" target="_blank">Google Scholar</a>] 
                [<a href="#" target="_blank">DBLP</a>] 
                [<a href="https://github.com/zhangdian617" target="_blank">GitHub</a>]
                [<a href="#" target="_blank">中文主页</a>]
            </div>
        </div> <!-- 关闭 核心信息区域 div -->
    </div> <!-- 关闭 右侧信息 col-sm-9 -->

</div>


<!-- 3. 个人简介 (Biography) -->

<div class="header">Biography</div>

<div class="text-justify">
    <p>
        <b>Dian Zhang</b> is currently a tenured Associate Professor and Ph.D. Supervisor at <b>Lingnan University</b>. She serves as the <b>Associate Dean</b> of the School of Data Science and the <b>Head</b> of the Division of Industrial Data Science. Her research interests span the fields of <b>mobile computing, smart healthcare, and data analytics</b>. To date, she has published approximately 60 papers in top international conferences and journals, with the majority being <b>first-authored by herself or  graduate students under her supervision</b>. The total amount of research funding(PI/CI) exceeds 10 Million Yuan.
    </p>
    <p>
        As one of the earliest researchers to <b>pioneer device-free localization</b> and behavior recognition technologies, she designed novel algorithms for device-free object positioning and sensing, helping to establish new research directions in the field. Her research excellence has been recognized with prestigious awards, including: 2019 Ministry of Education Natural Science Second Prize (教育部自然科学二等奖), 2022 Shenzhen Natural Science Award First Prize (深圳市自然科学一等奖), 2019 Pacific Insurance Company Academic Achievement Award.
    </p>
    <p>
        Her work in smart dental (healthcare) received 2024 Chinese Stomatological Association Annual Conference First Prize (corresponding author)(中华口腔医学会年会一等壁报), and International Association for Dental Research Southeast Asian Division (IADR-SEA) Research award (国际牙科研究协会亚太区研究贡献奖). Due to the contribution in smart dental, she was appointed <b>Honorary Professor</b> by the <b>Faculty of Dentistry at the University of Hong Kong</b> (ranked <b>2<sup>nd</sup> globally in Dentistry</b> by QS World University Rankings).
    </p>
</div>

<!-- 4.  Interest -->
<div class="header">Research Interest</div>
<div class="research-topics">
    <!-- 研究领域 -->
    <span class="topic-tag">Artificial Intelligence</span>
    <span class="topic-tag">Machine Learning</span>
    <span class="topic-tag">Smart Healthcare</span>
    <span class="topic-tag">Data Analytics</span>
    <span class="topic-tag">Internet of Things</span>
    <span class="topic-tag">Mobile Computing</span>
    <span class="topic-tag">RFID systems</span>
    <span class="topic-tag">Pervasive Computing</span>
    <span class="topic-tag">Networking and Distributed Systems</span>
    <span class="topic-tag">Wireless Sensor Networks</span>
</div>

<p style="color: red; font-weight: bold; margin-top: 20px;">
  I am currently looking for outstanding post-doctoral and graduate students, who are interested in my research area! Please contact me by email!
</p>

<!-- 5. 新闻动态 (News) -->
<div class="header">News</div>

<!-- 这里会自动加载 _news 文件夹里的内容 -->