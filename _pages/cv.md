---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

Education
======
* 한신대학교 AISW계열 학사 과정, 2025 - 현재

Projects
======
* **개인 포트폴리오 웹사이트 제작** (2025.09)
  * Jekyll과 Minimal Mistakes 테마를 사용하여 개인 기술 블로그 및 포트폴리오 구축
  * GitHub Pages를 통한 사이트 배포 및 관리
  * *포트폴리오 메뉴에서 더 자세한 내용을 확인할 수 있습니다.*

Skills
======
* **Programming Languages:**
  * Python
  * C
  * HTML
* **Tools & Technologies:**
  * Git
  * Jekyll
  * GitHub Pages

Publications
======
  <ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
Talks
======
  <ul>{% for post in site.talks reversed %}
    {% include archive-single-talk-cv.html  %}
  {% endfor %}</ul>
  
Teaching
======
  <ul>{% for post in site.teaching reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>