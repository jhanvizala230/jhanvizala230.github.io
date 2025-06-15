---
layout: page
title: About
permalink: /about/
weight: 3
---

# **About Me**

Hi I am **{{ site.author.name }}** :wave:,<br>
Welcome to my portfolio!I’m a Software Engineer and Machine Learning Specialist; with more than 3 years of experience in cloud-native API development, full-stack systems, and advanced AI solutions. I specialize in:

- Large Language Models (LLMs) and Generative AI
- Multilingual TTS and VITS architectures
- ML pipelines, model optimization, and MLOps
- Scalable deployments on GCP, Azure AKS, and Kubernetes

I’ve worked across diverse domains including document automation, speech synthesis, and image segmentation, blending engineering and research to deliver impactful AI products.

Explore some of my best work — both from industry and my own experiments.

<div class="row">
{% include about/skills.html title="Tools & Platforms" source=site.data.tools_platforms %}
{% include about/skills.html title="Devops & CLoud" source=site.data.devops %}
{% include about/skills.html title="ML Frameworks" source=site.data.ml %}
</div>
<div class="row">
{% include about/skills.html title="Data Engineering" source=site.data.data_eng %}
{% include about/skills.html title="Soft Skills" source=site.data.soft_skills %}
{% include about/skills.html title="Others" source=site.data.other %}

</div>

<div class="row">
{% include about/timeline.html %}
</div>