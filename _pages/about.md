---
permalink: /
title: "About"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

Hello! I am a PhD student researcher at the [School of Computing & Augmented Intelligence, Arizona State University](https://scai.engineering.asu.edu/), where I am fortunate to be advised by [Lindsay Sanneman](https://www.lindsaysanneman.com) and associated with the HEART AI Lab.

My research is grounded in AI Reasoning, Planning, and Sequential Decision-Making frameworks. I investigate the performance of generative AI models at various reasoning tasks for sequential decision-making, explore how benchmarks assess relevant constructs, and design agentic frameworks that are reliable and trustworthy.

My research interests also span Human-AI interaction, exploring how humans can augment AI with guidance via {domain & commonsense} knowledge, preferences, intuition, etc. And how AI can assist humans by offering data, compute, {narrow & broad} intelligence capabilities. I also have a broader interest in AI governance and policy. 

---

<div class="news-section">
<h1>News & Updates</h1>
<div class="news-container">
{% for item in site.data.news %}
<div class="news-item">
<span class="news-date">{{ item.date }}</span>
<span class="news-content">{{ item.content | markdownify | remove: '<p>' | remove: '</p>' | strip }}</span>
</div>
{% endfor %}
</div>
</div>

---

Before PhD, in what now feels like a previous life, I worked in Sensor Fusion, Analytics, and Networks across Nokia Networks, Forus Health, and WIPRO Ltd. I also worked as a Software Engineer at Accenture and as a Consulting Resource Person at the Board of IT Education Standards, Bengaluru. I explored research in Information Theory and Network Coding at Texas A&M University, College Station, as a Graduate Merit Scholar in the Computer Engineering Systems Group. I obtained my Bachelor's degree, majoring in Electronics & Telecommunication Engineering at PES University, Bengaluru. I consider myself fortunate to have had the exposure and opportunity to work in many different technical fields, and grateful to have met great people!


# Hobbies & Interests
In my free time, I enjoy trekking and biking. I have trekked in the Himalayas twice. I also listen to a wide variety of music and soundtracks and dabble in amateur video scoring. I used to be a district-level cricket player in my teens, and follow sporting events around the world.

![Design ECC 1 bottom](https://github.com/user-attachments/assets/8c0d6646-48b8-4df9-96c5-13ee16aa950a)
<div style="text-align: right;">
    Here's a fun function used in Elliptical Curve Cryptography!
</div>

<br>
<br>
<br>
<br>



This website is last updated: Sep 2025
