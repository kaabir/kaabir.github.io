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

<span class='anchor' id='About-Me'></span>

Hi! I am Syed Kaabir Ali. I am a Ph.D. student at the [Active Cell Matter](https://www.lpens.ens.psl.eu/research/biophys/equipe-19/?lang=en)  at [École normale supérieure](https://www.lpens.ens.psl.eu/), and affiliated with the Beijing Key Laboratory of Security and Privacy in Intelligent Transportation. I am advised by Prof. [Julie Plastino](http://faculty.bjtu.edu.cn/5608/), [Nathalie Delghyr](http://faculty.bjtu.edu.cn/9120/) and Assistant Prof. [Ayako Yamada](http://faculty.bjtu.edu.cn/9306/). Prior to my Ph.D. career, I received the M.S. degree with specilization in [Qingdao Agricultural University](https://www.qau.edu.cn/) in 2017, and the M.S. degree in software engineering from [Beijing Jiaotong University](https://bjtu.edu.cn/) in 2022.

Currently, my research has centered on:

- **AI Security:** backdoor attacks and defenses, adversarial attacks and defenses.

* **Safety Testing**:  testing and evaluation for autonomous driving algorithms, modules, and systems.

* **Data Augmentation**: image or video generation, especially focus on generative data augmentation (GDA) in autonomous driving scenarios.

* **Autonomous Driving Security**: attacks and defenses against the physical world, sensors, algorithms and automonous driving systems.

* **Reinforcement Learning**: safety reinforcement learning (SRL), robustness reinforcement learning and offline reinforcement learning for autonomous driving systems.

📮: I am always looking for related colaboration. If you are interested to chat with me, feel free to drop me an <a href="mailto:wuyalun1@bjtu.edu.cn" target="_blank">email</a>.





{% include_relative includes/News.md %}



{% include_relative includes/Publications.md %}



{% include_relative includes/Honors.md %}



{% include_relative includes/Educations.md %}



{% include_relative includes/Projects.md %}
