---
layout: page-w-banner
title: 프로젝트
bannerTitle: 레이븐코인 프로젝트
bannerImage: /assets/img/pages/exchanges/exchange-banner.jpg
permalink: /projects/
---

{% assign sorted_projects = site.data.projects | sort: "name" %}

<div class="wrapper mt-16 pb-20">
  <h2>현재 레이븐코인 커뮤니티 프로젝트</h2>
    <p>이하 모든 프로젝트는 레이븐코인 커뮤니티에 의해 운영되고 있습니다.</p>
    <br>
    <p>프로젝트 추가를 원하시면,  <a href="https://github.com/RavenProject/ravenproject.github.io/blob/master/_data/projects.yml">이 깃헙 웹페이지 데이터</a> 로 PR 신청을 해주시길 바랍니다.</p>
    <br>  
    <h3>목록</h3>
      <ul>
      {% for project in sorted_projects %}
          <li><a href="#{{ project.name }}">{{ project.name }}</a></li>
      {% endfor %}
      </ul>
      <br><br>
      {% for project in sorted_projects %}
          <h3 id="{{ project.name }}">{{ project.name }}</h3>          
          <p>{{ project.description }}</p>
          <h4>프로젝트 웹사이트</h4>
          <ul>
          {% for site in project.project_sites %}
          <li><a href="{{ site.url }}">{{ site.name }}</a></li>
          {% endfor %}
          </ul>
          {% if project contains "roadmap" %}
          <h4>프로젝트 로드맵</h4>
          <ul>
          {% for value in project.roadmap %}
          <li>{{ value.name }} -- {{ value.value }}</li>
          {% endfor %}
          </ul>
          {% endif %}
          {% if project contains "social" %}
          <h4>소통 채널</h4>
          <ul>
          {% for site in project.social %}
          <li><a href="{{ site.url }}">{{ site.name }}</a></li>
          {% endfor %}
          </ul>
          {% endif %}
          <br><br>
      {% endfor %}
</div>
