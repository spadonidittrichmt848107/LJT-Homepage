---
permalink: /
title: "Junteng Liu"
author_profile: true
redirect_from:
  - /about/
  - /about.html
---

I am a first-year PhD candidate at the [HKUST NLP Group](https://hkust-nlp.github.io/), Hong Kong University of Science and Technology. My research focuses on natural language processing and machine learning.

Education
======
* **Ph.D. in Computer Science**, Hong Kong University of Science and Technology (HKUST), 2024-Present.
* **B.Eng.**, Shanghai Jiao Tong University (SJTU), 2020-2024. I graduated in June 2024.

Research Interests
======
* LLM Reasoning and Reinforcement Learning
* Hallucination in Vision-Language Models (VLM)
* LLM Truthfulness and Interpretability

Research Experience
======
* **Research Intern**, MINIMAX, February 2025 - Present.
* **Research Intern**, Tencent WXG, June 2024 - September 2024. Advisor: Zifei Shan.
* **Research Intern**, Shanghai AI Lab, June 2023 - December 2023. Advisor: Prof. Yu Cheng.

Advising
======
My PhD supervisor is Professor Junxian He, who also advised me during my undergraduate studies at SJTU. The HKUST NLP Group is led by Professor Junxian He and focuses on natural language processing research.

Awards
======
* Zhiyuan Honor Scholarship, Shanghai Jiao Tong University.

Skills
======
My research skill set includes natural language processing and machine learning, with the research interests listed above.

Publications
======
{% for category in site.publication_category %}
  {% assign category_publications = site.publications | where: "category", category[0] | sort: "order" %}
  {% if category_publications.size > 0 %}
    <h2>{{ category[1].title }}</h2>
    {% for post in category_publications %}
      {% include archive-single.html %}
    {% endfor %}
  {% endif %}
{% endfor %}

Contact Information
======
* Email: [jliugi@connect.ust.hk](mailto:jliugi@connect.ust.hk)
* GitHub: [Vicent0205](https://github.com/Vicent0205)
* [Google Scholar](https://scholar.google.com/citations?hl=en&user=tbK9jl4AAAAJ&view_op=list_works&sortby=pubdate)
* X (Twitter): [@junteng88716710](https://twitter.com/junteng88716710)
