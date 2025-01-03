---
layout: single
author_profile: true
classes: wide
header:
  overlay_color: "#000"
  overlay_filter: "0.5"
  overlay_image: /assets/images/header-bg.jpg  # 建议使用一张漂亮的校园或城市风光照片
---

<style>
body {
  font-family: 'Lato', 'Source Sans Pro', -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, 'Helvetica Neue', Arial, sans-serif;
  font-weight: 300;
  line-height: 1.8;
}

h1, h2, h3 {
  font-family: 'Montserrat', sans-serif;
  font-weight: 700;
  color: #4169E1;  /* 使用蓝色标题，类似参考网站 */
}

.page__hero--overlay {
  min-height: 400px;
}

/* 隐藏底部栏 */
.page__footer {
  display: none !important;
}

/* 调整链接颜色 */
a {
  color: #4169E1;
  text-decoration: none;
}

/* 调整内容区域样式 */
.page__content {
  margin-top: 2em;
  max-width: 800px;
  margin-left: auto;
  margin-right: auto;
}

/* 调整教育经历样式 */
.notice {
  background-color: #f8f9fa;
  border-radius: 4px;
  padding: 1.5em;
  margin: 1em 0;
}
</style>

# Hello, I am Yichuan Ma.

I am a PhD Candidate at Fudan University. I am currently working as a research intern at InternLM team, Shanghai AI Laboratory. My research interests focus on synthetic data generation and its applications.

## Email

* mayichuan@pjlab.org.cn

## Education and Experience

{% capture education-text %}
* **Fudan University** (2024 - Present)  
  Ph.D. Student in Computer Science
  
* **Shanghai Jiao Tong University** (2020 - 2024)  
  B.E. in Artificial Intelligence

* **InternLM Team, Shanghai AI Laboratory** (2024 - Present)  
  Research Intern
{% endcapture %}

<div class="notice">
  {{ education-text | markdownify }}
</div>

## Research Interests

* Synthetic Data Generation
* Large Language Models
* AI Applications 