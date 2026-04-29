---
permalink: /
title: ""
author_profile: true
redirect_from: 
  - /about/
  - /about.html
  - /cv/
  - /resume
---

Biography
======
Dr. Xue Lei is a scholar in Management Science. His research focuses on corporate sustainable development, environmental policy impacts, technological innovation, and regional economics. His research has been published in leading journals including *Technology in Society*, *Economics Letters*, *International Review of Financial Analysis*, *Journal of Environmental Management*, *Journal of Cleaner Production*, *Journal of Manufacturing Technology Management*, *Journal of Engineering and Technology Management*, and *Energy Economics*.

Contact
======
* **Affiliation:** School of Management, Shanghai University
* **Email:** leixue187@gmail.com; leixue_work@shu.edu.cn
* **ORCID:** [0000-0001-5635-6784](https://orcid.org/0000-0001-5635-6784)
* **Google Scholar:** [Profile](https://scholar.google.com/citations?user=Fl9fzV8AAAAJ&hl=zh-CN)
* **ResearchGate:** [Profile](https://www.researchgate.net/profile/Xue-Lei-20/research)

Academic Appointments
======
* Editorial Board Member, *Oeconomia Copernicana*
* Editorial Board Member, *Journal of East European Management Studies*
* Editorial Board Member, *Human Resources Management and Services*
* Associate Editor, *Politická ekonomie*

Publications
======
{% for post in site.publications reversed %}
1. {{ post.citation }}
{% endfor %}
