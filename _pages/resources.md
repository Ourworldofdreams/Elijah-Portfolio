### 📰 What I’m Reading: Cybersecurity News and Updates

<div id="rss-news">
  {% for item in site.data.rss_feed.news %}
    <div>
      <strong><a href="{{ item.url }}">{{ item.title }}</a></strong>
      <p>{{ item.description }}</p>
    </div>
    <hr>
  {% endfor %}
</div>

---

### 🛠 Cybersecurity Tools I Use and Recommend

<div id="rss-tools">
  {% for item in site.data.rss_feed.tools %}
    <div>
      <strong><a href="{{ item.url }}">{{ item.title }}</a></strong>
      <p>{{ item.description }}</p>
    </div>
    <hr>
  {% endfor %}
</div>


---
