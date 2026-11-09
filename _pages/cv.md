---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

Education
======
* **Ph.D. in Computer Science**, Hong Kong University of Science and Technology (HKUST), 2024-Present.
* **B.Eng.**, Shanghai Jiao Tong University (SJTU), 2020-2024. Graduated in June 2024.

Research Focus and Skills
======
* Natural Language Processing
* Machine Learning

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

Academic Advising
======
* PhD supervisor: Professor Junxian He, HKUST NLP Group.
* Undergraduate adviser: Professor Junxian He, SJTU.

Honors and Awards
======
* Zhiyuan Honor Scholarship, Shanghai Jiao Tong University.

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

Contact
======
* Email: [jliugi@connect.ust.hk](mailto:jliugi@connect.ust.hk)
* GitHub: [Vicent0205](https://github.com/Vicent0205)
* [Google Scholar](https://scholar.google.com/citations?hl=en&user=tbK9jl4AAAAJ&view_op=list_works&sortby=pubdate)
* X (Twitter): [@junteng88716710](https://twitter.com/junteng88716710)
