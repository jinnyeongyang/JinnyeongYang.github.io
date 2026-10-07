---
layout: about
title: about
permalink: /
subtitle: MS Student, <a href='https://www.kaist.ac.kr/en/'>KAIST</a> · Advised by Kuk-Jin Yoon · Multi-Agent Systems &amp; Cooperative AI

profile:
  align: right
  image: prof_pic.jpg
  image_circular: false # crops the image to make it circular
  more_info: >
    <p>ME Building (N7-4) #5123</p>
    <p>291 Daehak-ro, Yuseong-gu</p>
    <p>Daejeon 34141, South Korea</p>

selected_papers: false # rendered in the page body below instead, so honors & awards can go last
social: false # social icons are shown in the top navbar instead (enable_navbar_social in _config.yml)

announcements:
  enabled: false # rendered in the page body below instead, so honors & awards can go last
  scrollable: true # adds a vertical scroll bar if there are more than 3 news items
  limit: 5 # leave blank to include all the news in the `_news` folder

latest_posts:
  enabled: false # set to true if you want to show blog posts on the homepage
  scrollable: true
  limit: 3
---

Hi, I'm **Jinnyeong Yang**, a Master's student in the Division of Future Vehicle at
[KAIST](https://www.kaist.ac.kr/en/), advised by Professor **Kuk-Jin Yoon**. I received my
B.S. in Mechanical Engineering from Korea University, graduating *Magna Cum Laude*.

My research interests lie in **multi-agent reinforcement learning**, **cooperative AI**, and
**zero-shot coordination**. Recently, I worked on coordination with unfamiliar partners under partial
observability. I have also worked on text-guided driving scene generation and data augmentation using
generative models, as well as automatic 4D LiDAR annotation using foundation models.

**I am currently looking for Ph.D. opportunities** in multi-agent systems and cooperative AI.
If you think I would be a good fit for your group, please feel free to contact me.

You can find my [publications](/publications/) here and my full [CV](/cv/) as well. Feel free to
reach out by email or any of the links at the top of the page.

<!-- news and selected publications are rendered here (not by the about layout) so that
     honors & awards can come last. clear: both keeps each section below the profile photo. -->
<div style="clear: both">
<h2><a href="{{ '/news/' | relative_url }}" style="color: inherit">news</a></h2>
{% include news.liquid limit=true %}

<h2><a href="{{ '/publications/' | relative_url }}" style="color: inherit">selected publications</a></h2>
{% include selected_papers.liquid %}

<h2>honors &amp; awards</h2>
<div class="news">
  <div class="table-responsive">
    <table class="table table-sm table-borderless">
      <tr><th scope="row" style="width: 20%">2026</th><td>Kia Scholarship Foundation Scholarship</td></tr>
      <tr><th scope="row" style="width: 20%">2025</th><td>Magna Cum Laude, Korea University</td></tr>
      <tr><th scope="row" style="width: 20%">2024</th><td>IMM Hope Foundation Scholarship</td></tr>
      <tr><th scope="row" style="width: 20%">2021</th><td>2nd Place, Beginner Division, 19th Korea Robot Aircraft Competition</td></tr>
    </table>
  </div>
</div>
</div>
