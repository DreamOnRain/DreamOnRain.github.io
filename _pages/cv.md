---
layout: archive
title: ""
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

Education
======
* Master of Computing, [National University of Singapore](https://nus.edu.sg/), Jan. 2024 - June 2025
* Bacholer of Engineering in Telecommunication Engineering, [South China Normal University](https://www.scnu.edu.cn/), Sept. 2015 - June 2019


Work Experience
======
* Fall 2024: [Sound and Music Computing Lab @NUS](https://smcnus.comp.nus.edu.sg/)
  * Student Research Assistant
  * Supervisor: Associate Professor [WANG Ye](https://www.comp.nus.edu.sg/cs/people/wangye/)

* July 2019 to Jan. 2024: [Shenzhen Skyworth-RGB Electronics Co., LTD](https://www.skyworth.com/)
  * Android Engineer


Skills
======
* Machine Learning, Deep Learning
  * Speech Recognition, Pitch Detection
  * pytorch, speechbrain
* Android
  * Android Framework
  * Android Recovery
  * Android Build
* Coding
  * Python, Java, C/C++


Honor Awards
======
* Second prize of the Innovation Award, 2018
* University Individual Scholarship (Ethics), 2018
* First prize of University Comprehensive Scholarship, 2017
* First prize of 18th Guangdong College Students Physics Experiment Design Competition, 2017
* Third Prize in C/C++ Programming Group of the Eighth Lanqiao Cup National Software and Information Technology Professionals Competition, 2017
* Third prize of China Undergraduate Mathematical Contest in Modelling, 2017
* Third prize of Mathematical Contest in Modelling of South China Normal University, 2016
* Second prize of University Mathematics Contest, 2015
* Second prize of 31st and 32nd Electronic Design Competition, 2015


Publications
======
  {% for post in site.publications reversed %}
    [{{ post.title }}]({{ post.paperurl}})
  {% endfor %}

