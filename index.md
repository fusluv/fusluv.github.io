---
layout: default
---

<body>
  <div class="index-wrapper">
    <div class="aside">
      <div class="info-card">
        <h1>fusluv</h1>
        <a href="http://weibo.com/u/3177380934" target="_blank"><img src="http://www.weibo.com/favicon.ico" alt="" width="25"/></a>
        <a href="http://tieba.baidu.com/home/main?un=Invictus_S" target="_blank"><img src="https://tieba.baidu.com/favicon.ico" alt="" width="25"/></a>
        <a href="https://www.zhihu.com/people/vanilla-3/activities" target="_blank"><img src="https://www.zhihu.com/favicon.ico" alt="" width="25"/></a>
        <a href="https://github.com/fusluv/" target="_blank"><img src="https://github.com/favicon.ico" alt="" width="25"/></a>
        <a href="https://space.bilibili.com/10742992/" target="_blank"><img src="https://www.bilibili.com/favicon.ico" alt="" width="25"/></a>
        <a href="http://steamcommunity.com/id/luv_is_4ever/" target="_blank"><img src="http://store.steampowered.com/favicon.ico" alt="" width="25"/></a>
      </div>
      <div id="particles-js"></div>
    </div>

    <div class="index-content">
      <ul class="artical-list">
        {% for post in site.categories.blog %}
        <li>
          <a href="{{ post.url }}" class="title">{{ post.title }}</a>
          <div class="title-desc">{{ post.description }}</div>
        </li>
        {% endfor %}
      </ul>
    </div>
  </div>
</body>
