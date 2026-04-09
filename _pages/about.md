---
permalink: /
title: ""
excerpt: ""
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

{% if site.google_scholar_stats_use_cdn %}
{% assign gsDataBaseUrl = "https://cdn.jsdelivr.net/gh/" | append: site.repository | append: "@" %}
{% else %}
{% assign gsDataBaseUrl = "https://raw.githubusercontent.com/" | append: site.repository | append: "/" %}
{% endif %}
{% assign url = gsDataBaseUrl | append: "google-scholar-stats/gs_data_shieldsio.json" %}

<span class='anchor' id='about-me'></span>

<!-- Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. Suspendisse condimentum, libero vel tempus mattis, risus risus vulputate libero, elementum fermentum mi neque vel nisl. Maecenas facilisis maximus dignissim. Curabitur mattis vulputate dui, tincidunt varius libero luctus eu. Mauris mauris nulla, scelerisque eget massa id, tincidunt congue felis. Sed convallis tempor ipsum rhoncus viverra. Pellentesque nulla orci, accumsan volutpat fringilla vitae, maximus sit amet tortor. Aliquam ultricies odio ut volutpat scelerisque. Donec nisl nisl, porttitor vitae pharetra quis, fringilla sed mi. Fusce pretium dolor ut aliquam consequat. Cras volutpat, tellus accumsan mattis molestie, nisl lacus tempus massa, nec malesuada tortor leo vel quam. Aliquam vel ex consectetur, vehicula leo nec, efficitur eros. Donec convallis non urna quis feugiat. -->

Greetings! I'm a second-year Ph.D. student jointly supervised by Fudan University and [Shanghai AI Lab](https://www.shlab.org.cn/), specializing in artificial intelligence. I earned my bachelor's degree in AI from Shanghai Jiao Tong University. I'm also interning at the [InternLM](https://github.com/InternLM) team.

My research interests focus on Large Language Models (LLMs). My work lies in improving LLMs' reasoning capabilities in specialized domains through synthetic data generation and reinforcement learning.

I'm currently looking for collaborations, feel free to contact me.

<!-- My research interest includes neural machine translation and computer vision. I have published more than 100 papers at the top international AI conferences with total <a href='https://scholar.google.com/citations?user=DhtAFkwAAAAJ'>google scholar citations <strong><span id='total_cit'>260000+</span></strong></a> (You can also use google scholar badge <a href='https://scholar.google.com/citations?user=DhtAFkwAAAAJ'><img src="https://img.shields.io/endpoint?url={{ url | url_encode }}&logo=Google%20Scholar&labelColor=f6f6f6&color=9cf&style=flat&label=citations"></a>). -->


# 🔥 News

- *2026.04*: &nbsp;🎉🎉 Our paper **Timely Machine** is accepted by [ACL 2026](https://2026.aclweb.org/).
- *2026.02*: We release [InternS1-Pro](https://huggingface.co/internlm/Intern-S1-Pro), an advanced scientific reasoning model with strong capabilities.
- *2025.09*: &nbsp;🎉🎉 Our paper **Mixing Expert Knowledge** is accepted by [NIPS 2025](https://neurips.cc/).
- *2025.08*: &nbsp;🎉🎉 Our paper **UnitCoder** is accepted by [EMNLP 2025](https://2025.emnlp.org/).
<details>
<summary><strong>More news</strong></summary>
<ul>
<li><em>2025.07</em>: We release <a href="https://github.com/InternLM/Intern-S1">InternS1</a>, an advanced open-source multimodal reasoning model.</li>
<li><em>2025.04</em>: We release <a href="https://intern.openxlab.org.cn/internthinker/go-game/"><strong>InternThinker Go</strong></a>, the <strong>first</strong> general LLM with expert level Go performance.</li>
<li><em>2025.04</em>: We release <a href="https://github.com/InternLM/InternBootcamp"><strong>InternBootCamp</strong></a>, a library of bootcamp environments for training LRMs.</li>
</ul>
</details>

# 📝 Publications 

## First-author Papers

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ACL, 2026</div><img src='images/paper_imgs/Timely_Machine.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Timely Machine: Awareness of Time Makes Test-Time Scaling Agentic](https://arxiv.org/abs/2601.16486)

**Yichuan Ma**, Linyang Li, Yongkang chen, Peiji Li, Xiaozhe Li, Qipeng Guo, Dahua Lin, Kai Chen

<!-- [![Code](https://img.shields.io/badge/Code-GitHub-181717?style=flat&labelColor=f6f6f6&logo=github&logoColor=181717)](https://github.com/Entarochuan/UnitCoder) -->

<!-- [**Project**](https://scholar.google.com/citations?view_op=view_citation&hl=zh-CN&user=DhtAFkwAAAAJ&citation_for_view=DhtAFkwAAAAJ:ALROH1vI_8AC) <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong>
- Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet.  -->


</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">NeurIPS, 2025</div><img src='images/paper_imgs/Mixing_Expert_Knowledge.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Mixing Expert Knowledge: Bring Human Thoughts Back To the Game of Go](https://neurips.cc/virtual/2025/poster/117166)

**Yichuan Ma**, Linyang Li, Yongkang Chen, Peiji Li, Jiasheng Ye, Qipeng Guo, Dahua Lin, Kai Chen

[![Play with](https://img.shields.io/badge/Play%20with%20our%20model-DEMO-ffd54f?style=flat&labelColor=f6f6f6&logo=data%3Aimage%2Fsvg%2Bxml%3Bbase64%2CPHN2ZyBpZD0iTGF5ZXJfMSIgZW5hYmxlLWJhY2tncm91bmQ9Im5ldyAwIDAgNTEyIDUxMiIgaGVpZ2h0PSI1MTIiIHZpZXdCb3g9IjAgMCA1MTIgNTEyIiB3aWR0aD0iNTEyIiB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciPjxnIGlkPSJYTUxJRF8yNTc1XyI+PHBhdGggaWQ9IlhNTElEXzE3OTlfIiBkPSJtMTAgMTBoNDkydjQ5MmgtNDkyeiIgZmlsbD0iI2ZmY2Q2OSIvPjxwYXRoIGlkPSJYTUxJRF8xNjY1XyIgZD0ibTU0IDU0aDQwNHY0MDRoLTQwNHoiIGZpbGw9IiNmZmRhOGYiLz48Y2lyY2xlIGlkPSJYTUxJRF8xMDIxXyIgY3g9IjE1NSIgY3k9IjM1NyIgZmlsbD0iI2ZmZiIgcj0iNDQiLz48Y2lyY2xlIGlkPSJYTUxJRF8xNzM3XyIgY3g9IjI1NiIgY3k9IjM1NyIgZmlsbD0iI2ZmZiIgcj0iNDQiLz48Y2lyY2xlIGlkPSJYTUxJRF8xNzQwXyIgY3g9IjM1NyIgY3k9IjM1NyIgZmlsbD0iIzZkOTJhYyIgcj0iNDQiLz48Y2lyY2xlIGlkPSJYTUxJRF8xNzYxXyIgY3g9IjE1NSIgY3k9IjE1NSIgZmlsbD0iI2ZmZiIgcj0iNDQiLz48Y2lyY2xlIGlkPSJYTUxJRF8xNzQzXyIgY3g9IjM1NyIgY3k9IjE1NSIgZmlsbD0iIzZkOTJhYyIgcj0iNDQiLz48Y2lyY2xlIGlkPSJYTUxJRF8xNzY3XyIgY3g9IjM1NyIgY3k9IjI1NiIgZmlsbD0iI2ZmZiIgcj0iNDQiLz48ZyBpZD0iWE1MSURfMl8iPjxwYXRoIGlkPSJYTUxJRF81NDdfIiBkPSJtNTQgNDRjLTUuNTIyIDAtMTAgNC40NzctMTAgMTB2NDA0YzAgNS41MjMgNC40NzggMTAgMTAgMTBoNDA0YzUuNTIyIDAgMTAtNC40NzcgMTAtMTB2LTQwNGMwLTUuNTIzLTQuNDc4LTEwLTEwLTEwem0zNTYuMDU3IDEyMWgzNy45NDN2ODFoLTM3Ljk0M2MtMy41MDUtMTguNjMzLTE2LjYwMy0zMy45MTQtMzMuOTU3LTQwLjUgMTcuMzU0LTYuNTg2IDMwLjQ1Mi0yMS44NjcgMzMuOTU3LTQwLjV6bTAgMTgyYy0zLjUwNS0xOC42MzMtMTYuNjAzLTMzLjkxNC0zMy45NTctNDAuNSAxNy4zNTQtNi41ODYgMzAuNDUyLTIxLjg2NyAzMy45NTctNDAuNWgzNy45NDN2ODF6bS0zNDYuMDU3IDB2LTgxaDgxdjM3Ljk0M2MtMjEuNzY5IDQuMDk1LTM4Ljk2MiAyMS4yODctNDMuMDU3IDQzLjA1N3ptMzcuOTQzLTE4MmM0LjA5NSAyMS43NyAyMS4yODcgMzguOTYyIDQzLjA1NyA0My4wNTd2MzcuOTQzaC04MXYtODF6bTUzLjA1Ny00NGMxOC43NDQgMCAzMy45OTMgMTUuMjQ2IDM0IDMzLjk4NyAwIC4wMDQtLjAwMS4wMDktLjAwMS4wMTNzLjAwMS4wMDkuMDAxLjAxM2MtLjAwNyAxOC43NDEtMTUuMjU2IDMzLjk4Ny0zNCAzMy45ODctMTguNzQ4IDAtMzQtMTUuMjUyLTM0LTM0czE1LjI1Mi0zNCAzNC0zNHptOTEgNDR2ODFoLTgxdi0zNy45NDNjMjEuNzY5LTQuMDk1IDM4Ljk2Mi0yMS4yODcgNDMuMDU3LTQzLjA1N3ptNTcuOTQzIDBjMy41MDUgMTguNjMzIDE2LjYwMyAzMy45MTQgMzMuOTU3IDQwLjUtMTcuMzU0IDYuNTg2LTMwLjQ1MiAyMS44NjctMzMuOTU3IDQwLjVoLTM3Ljk0M3YtODF6bTIuNTU3IDE3Mi45Yy02LjU4Ni0xNy4zNTQtMjEuODY3LTMwLjQ1Mi00MC41LTMzLjk1N3YtMzcuOTQzaDM3Ljk0M2MzLjUwNSAxOC42MzMgMTYuNjAzIDMzLjkxNCAzMy45NTcgNDAuNS0xNC40MzMgNS40NzctMjUuOTIzIDE2Ljk2Ny0zMS40IDMxLjR6bS01MC41IDUzLjFjLTE4Ljc0OCAwLTM0LTE1LjI1Mi0zNC0zNHMxNS4yNTItMzQgMzQtMzQgMzQgMTUuMjUyIDM0IDM0LTE1LjI1MiAzNC0zNCAzNHptLTUwLjUtNTMuMWMtNi41ODYtMTcuMzU0LTIxLjg2Ny0zMC40NTItNDAuNS0zMy45NTd2LTM3Ljk0M2g4MXYzNy45NDNjLTE4LjYzMyAzLjUwNS0zMy45MTQgMTYuNjAzLTQwLjUgMzMuOTU3em0xMTcuNS04MS45YzAtMTguNzQ4IDE1LjI1Mi0zNCAzNC0zNHMzNCAxNS4yNTIgMzQgMzQtMTUuMjUyIDM0LTM0IDM0LTM0LTE1LjI1Mi0zNC0zNHptLTE2OCA2N2MxOC43NDggMCAzNCAxNS4yNTIgMzQgMzRzLTE1LjI1MiAzNC0zNCAzNC0zNC0xNS4yNTItMzQtMzQgMTUuMjUyLTM0IDM0LTM0em0xMCA4Ny4wNTdjMTguNjMzLTMuNTA1IDMzLjkxNC0xNi42MDMgNDAuNS0zMy45NTcgNi41ODYgMTcuMzU0IDIxLjg2NyAzMC40NTIgNDAuNSAzMy45NTd2MzcuOTQzaC04MXptMTAxIDBjMTguNjMzLTMuNTA1IDMzLjkxNC0xNi42MDMgNDAuNS0zMy45NTcgNi41ODYgMTcuMzU0IDIxLjg2NyAzMC40NTIgNDAuNSAzMy45NTd2MzcuOTQzaC04MXptOTEtMTkuMDU3Yy0xOC43NDggMC0zNC0xNS4yNTItMzQtMzRzMTUuMjUyLTM0IDM0LTM0IDM0IDE1LjI1MiAzNCAzNC0xNS4yNTIgMzQtMzQgMzR6bTAtMjAyYy0xOC43NDggMC0zNC0xNS4yNTItMzQtMzRzMTUuMjUyLTM0IDM0LTM0IDM0IDE1LjI1MiAzNCAzNC0xNS4yNTIgMzQtMzQgMzR6bS0xMC04Ny4wNTdjLTIxLjc2OSA0LjA5NS0zOC45NjIgMjEuMjg3LTQzLjA1NyA0My4wNTdoLTM3Ljk0M3YtODFoODF6bS0xMDEgNDMuMDU3aC0zNy45NDNjLTQuMDk1LTIxLjc3LTIxLjI4OC0zOC45NjItNDMuMDU3LTQzLjA1N3YtMzcuOTQzaDgxem0tMTAxLTgxdjM3Ljk0M2MtMjEuNzY5IDQuMDk1LTM4Ljk2MiAyMS4yODctNDMuMDU3IDQzLjA1N2gtMzcuOTQzdi04MXptLTgxIDMwM2gzNy45NDNjNC4wOTUgMjEuNzcgMjEuMjg3IDM4Ljk2MiA0My4wNTcgNDMuMDU3djM3Ljk0M2gtODF6bTMwMyA4MXYtMzcuOTQzYzIxLjc2OS00LjA5NSAzOC45NjItMjEuMjg3IDQzLjA1Ny00My4wNTdoMzcuOTQzdjgxem04MS0zMDNoLTM3Ljk0M2MtNC4wOTUtMjEuNzctMjEuMjg4LTM4Ljk2Mi00My4wNTctNDMuMDU3di0zNy45NDNoODF6Ii8+PHBhdGggaWQ9IlhNTElEXzczMV8iIGQ9Im01MDIgMGgtMjAxYy01LjUyMiAwLTEwIDQuNDc3LTEwIDEwczQuNDc4IDEwIDEwIDEwaDE5MXY0NzJoLTQ3MnYtNDcyaDE5MWM1LjUyMiAwIDEwLTQuNDc3IDEwLTEwcy00LjQ3OC0xMC0xMC0xMGgtMjAxYy01LjUyMiAwLTEwIDQuNDc3LTEwIDEwdjQ5MmMwIDUuNTIzIDQuNDc4IDEwIDEwIDEwaDQ5MmM1LjUyMiAwIDEwLTQuNDc3IDEwLTEwdi00OTJjMC01LjUyMy00LjQ3OC0xMC0xMC0xMHoiLz48cGF0aCBpZD0iWE1MSURfNzMyXyIgZD0ibTI1NiAyMGMyLjYzIDAgNS4yMS0xLjA3IDcuMDY5LTIuOTMgMS44NjEtMS44NiAyLjkzMS00LjQ0IDIuOTMxLTcuMDdzLTEuMDctNS4yMS0yLjkzMS03LjA3Yy0xLjg1OS0xLjg2LTQuNDM5LTIuOTMtNy4wNjktMi45M3MtNS4yMSAxLjA3LTcuMDcgMi45M2MtMS44NjEgMS44Ni0yLjkzIDQuNDQtMi45MyA3LjA3czEuMDY5IDUuMjEgMi45MyA3LjA3IDQuNDQgMi45MyA3LjA3IDIuOTN6Ii8+PC9nPjwvZz48L3N2Zz4%3D&logoWidth=18)](https://intern-chat.staging.openxlab.org.cn/internthinker/go-game/) [![Code](https://img.shields.io/badge/Code-GitHub-181717?style=flat&labelColor=f6f6f6&logo=github&logoColor=181717)](https://github.com/Entarochuan/InternGo-LoGos)

<!-- [**Project**](https://scholar.google.com/citations?view_op=view_citation&hl=zh-CN&user=DhtAFkwAAAAJ&citation_for_view=DhtAFkwAAAAJ:ALROH1vI_8AC) <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong>
- Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet.  -->

</div>
</div>


<div class='paper-box'><div class='paper-box-image'><div><div class="badge">EMNLP, 2025</div><img src='images/paper_imgs/unitcoder.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[UnitCoder: Scalable Code Synthesis from Pre-training Corpora](https://arxiv.org/abs/2502.11460)

**Yichuan Ma**, Yunfan Shao, Peiji Li, Demin Song, Qipeng Guo, Linyang Li, Xipeng Qiu, Kai Chen

[![Code](https://img.shields.io/badge/Code-GitHub-181717?style=flat&labelColor=f6f6f6&logo=github&logoColor=181717)](https://github.com/Entarochuan/UnitCoder)

<!-- [**Project**](https://scholar.google.com/citations?view_op=view_citation&hl=zh-CN&user=DhtAFkwAAAAJ&citation_for_view=DhtAFkwAAAAJ:ALROH1vI_8AC) <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong>
- Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet.  -->


</div>
</div>

## Co-author Papers

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Arxiv, 2026</div><img src='images/InternS1-Pro.png' alt="paper" width="85%"></div></div>
<div class='paper-box-text' markdown="1">

[Intern-S1-Pro: Scientific Multimodal Foundation Model at Trillion Scale
](https://arxiv.org/abs/2603.25040v2)

Lei Bai, Zhongrui Cai, Yuhang Cao, Maosong Cao, ... , **Yichuan Ma**, Zihan Ma, Sixuan Mi, Junzhi Ning, ...

<!-- [![Code](https://img.shields.io/badge/Code-GitHub-181717?style=flat&labelColor=f6f6f6&logo=github&logoColor=181717)](https://github.com/FlyingDutchman26/FastMCTS) -->

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Arxiv, 2025</div><img src='images/InternS1.png' alt="paper" width="90%"></div></div>
<div class='paper-box-text' markdown="1">

[Intern-S1: A Scientific Multimodal Foundation Model](https://arxiv.org/abs/2508.15763)

Yicheng Zou, Dongsheng Zhu, Lin Zhu, Tong Zhu, Yunhua Zhou, ... , **Yichuan Ma**, Zerun Ma, Ningsheng Ma ...

<!-- [![Code](https://img.shields.io/badge/Code-GitHub-181717?style=flat&labelColor=f6f6f6&logo=github&logoColor=181717)](https://github.com/FlyingDutchman26/FastMCTS) -->

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ACL, 2025</div><img src='images/paper_imgs/fastmcts.png' alt="paper" width="90%"></div></div>
<div class='paper-box-text' markdown="1">

[FastMCTS: A Simple Sampling Strategy for Data Synthesis](https://arxiv.org/abs/2502.11476)

Peiji Li, Kai Lv, Yunfan Shao, **Yichuan Ma**, Linyang Li, Xiaoqing Zheng, Xipeng Qiu, Qipeng Guo

[![Code](https://img.shields.io/badge/Code-GitHub-181717?style=flat&labelColor=f6f6f6&logo=github&logoColor=181717)](https://github.com/FlyingDutchman26/FastMCTS)

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">COLING, 2024</div><img src='images/paper_imgs/Case2Code.png' alt="paper" width="90%"></div></div>
<div class='paper-box-text' markdown="1">

[Case2Code: Scalable Synthetic Data for Code Generation](https://arxiv.org/abs/2407.12504)

Yunfan Shao, Linyang Li, **Yichuan Ma**, Peiji Li, Demin Song, Qinyuan Cheng, Shimin Li, Xiaonan Li, Pengyu Wang, Qipeng Guo, Hang Yan, Xipeng Qiu, Xuanjing Huang, Dahua Lin

[![Code](https://img.shields.io/badge/Code-GitHub-181717?style=flat&labelColor=f6f6f6&logo=github&logoColor=181717)](https://github.com/choosewhatulike/case2code)

</div>
</div>


<div class='paper-box'><div class='paper-box-image'><div><div class="badge">arXiv, 2024</div><img src='images/paper_imgs/InternLM-Math.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[InternLM-Math: Open Math Large Language Models Toward Verifiable Reasoning](https://arxiv.org/abs/2402.06332)

Huaiyuan Ying, Shuo Zhang, Linyang Li, Zhejian Zhou, Yunfan Shao, Zhaoye Fei, **Yichuan Ma**, Jiawei Hong, Kuikun Liu, Ziyi Wang, Yudong Wang, Zijian Wu, Shuaibin Li, Fengzhe Zhou, Hongwei Liu, Songyang Zhang, Wenwei Zhang, Hang Yan, Xipeng Qiu, Jiayu Wang, Kai Chen, Dahua Lin


</div>
</div>
<!-- Add more co-author papers here -->



<!-- # 🎖 Honors and Awards
- *2021.10* Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
- *2021.09* Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet.  -->

# 📖 Educations
<img src="images/FDU.png" alt="Fudan University" width="35" height="35"> *2024.09 - Now*, Ph.D. student in Computer Science, Fudan University and [Shanghai AI Lab](https://www.shlab.org.cn/) 

<img src="images/SJTU.png" alt="Shanghai Jiao Tong University" width="35" height="35"> *2020.09 - 2024.06*, Bachelor's degree in Artificial Intelligence, Shanghai Jiao Tong University 

<!-- # 💬 Invited Talks
- *2021.06*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
- *2021.03*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet.  \| [\[video\]](https://github.com/) -->

# 💻 Internships
- *2023.11 - Now*, Shanghai AI Lab, [InternLM Team](https://github.com/InternLM), China.

# 🎯 Hobbies

## <img src="images/go.svg" alt="Go" width="20" height="20"> Go
I am an amateur 5-dan Go player (currently ranked 9-dan on [FoxGo](https://www.foxwq.com/)), welcome anyone to a game!
<details>
<summary><strong>Some notable achievements</strong></summary>
<ul>
<li><strong>2021 Shanghai University Go League</strong>: Best Newcomer Award</li>
<li><strong>Suzhou Go League</strong>: Champion</li>
<li><strong>Suzhou Youth Go Championship</strong>: 3-time Champion</li>
</ul>
</details>

## <img src="images/badminton.svg" alt="badminton" width="20" height="20"> Badminton

Started playing badminton at the age of 6.

## <img src="images/SC2.png" alt="SC2" width="20" height="20"> StarCraft II

SC2 is the best game!