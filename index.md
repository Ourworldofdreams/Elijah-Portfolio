---
layout: home
author_profile: true
title: "Welcome to My Cybersecurity Portfolio"
---

**Hi, I’m Elijah Miller** 

I am a dedicated IT professional with hands-on experience in SOC operations, phishing analysis, malware forensics, and IT support. My passion lies in building robust security systems, threat detection, and ensuring strong network defense. 

**This portfolio showcases my technical projects, certifications, and skills as I continue to grow and contribute to the ever-evolving world of cybersecurity.**

---

### Explore My Work:
- [About Me](about)
- [Projects](projects)
- [Skills](skills)
- [Certifications](certifications)
- [Contact](contact)

---

### 🔒 Latest Cybersecurity Updates & Things I'm Into 
<div id="rss-feed">
  {% for item in site.data.rss_feed %}
    <div>
      <strong><a href="{{ item.url }}">{{ item.title }}</a></strong>
      <p>{{ item.description }}</p>
    </div>
    <hr>
  {% endfor %}
</div>
