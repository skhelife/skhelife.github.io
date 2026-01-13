---
permalink: /
title: "Welcome to my homepage!"
excerpt: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

<span id="about"></span>

I am a **third-year** Undergraduate Student (Ranking **7/202**) of **Computer Science and Technology (Top-notch Undergraduate Training Program)**, **Chongqing University**, China.

My research interests primarily center on **Large Language Models (LLMs)**, with a specific focus on:
* **Diffusion LLMs**
* **Multimodal LLMs**

I am deeply fascinated by the mechanisms of **reasoning** in large language models and exploring how to align them with **human cognition and logic** (Alignment & Reasoning).

🔥 **I am actively seeking research internship opportunities. Please feel free to contact me!**

📧 **Email:** skhelife@outlook.com  
💬 **Wechat:** skhelife

---

<h2 id="education" style="margin-top: 60px;">🎓 Education</h2>

**Chongqing University (CQU)**, China  
*B.Eng. in Computer Science and Technology (Top-notch Undergraduate Training Program)*, *Sept. 2023 - Present*
* **GPA:** 3.xx / 4.0
* **Ranking:** **7 / 202** (Top 3.5%)
* **Core Courses:** Data Structures and Algorithms, Machine Learning, Operating Systems, Computer Networks

---

<h2 id="awards" style="margin-top: 60px;">🏆 Honors & Awards</h2>

* **National Scholarship** (Top 0.2%), *2024*
* **Meritorious Winner**, MCM/ICM, *2024*
* **First Prize**, CQU Academic Scholarship, *2023, 2024*
* **Outstanding Student** of Chongqing University, *2024*

---

<h2 id="publications" style="margin-top: 60px;">📝 Publications</h2>

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}