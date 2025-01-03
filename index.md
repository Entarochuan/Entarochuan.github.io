---
layout: single
author_profile: true
classes: wide
header:
  overlay_color: "#000"
  overlay_filter: "0.5"
  overlay_image: /assets/images/header-bg.jpg  # 稍后添加背景图
---

# Welcome to My Academic Homepage

<div style="text-align: justify">
I am a PhD Candidate in [Your Field] at [Your University]. My research focuses on [Your Research Interests].
</div>

## News & Updates
{: .text-center}

{% capture notice-text %}
* **[2024.03]** Paper accepted at [Conference/Journal Name]
* **[2024.02]** Presented our work at [Conference Name]
* **[2024.01]** Started new project on [Project Name]
{% endcapture %}

<div class="notice--info">
  {{ notice-text | markdownify }}
</div>

## Research Interests
{: .text-center}

<div class="feature__wrapper">
  <div class="feature__item">
    <div class="archive__item">
      <div class="archive__item-body">
        <h3>Research Area 1</h3>
        <p>Brief description of your first research area.</p>
      </div>
    </div>
  </div>
  
  <div class="feature__item">
    <div class="archive__item">
      <div class="archive__item-body">
        <h3>Research Area 2</h3>
        <p>Brief description of your second research area.</p>
      </div>
    </div>
  </div>
  
  <div class="feature__item">
    <div class="archive__item">
      <div class="archive__item-body">
        <h3>Research Area 3</h3>
        <p>Brief description of your third research area.</p>
      </div>
    </div>
  </div>
</div>

## Selected Publications
{: .text-center}

{% capture notice-text %}
* **Paper Title 1**  
  Authors, Conference/Journal, Year  
  [PDF] [Code] [DOI]

* **Paper Title 2**  
  Authors, Conference/Journal, Year  
  [PDF] [Code] [DOI]
{% endcapture %}

<div class="notice">
  {{ notice-text | markdownify }}
</div> 