---
layout: home
title: CS 4650
nav_exclude: true
seo:
  type: Course
  name: Just the Class
---

# {{ site.tagline }}
{: .mb-2 }
{{ site.description }}
{: .fs-6 .fw-300 }

{% if site.announcements %}
{{ site.announcements.last }}
[Announcements](announcements.md){: .btn .btn-outline .fs-3 }
{% endif %}

- Location: Klaus Advanced Computing Building 2443
- Time: MW 5:00 pm - 6:15 pm
- [Piazza](https://piazza.com/gatech/fall2023/cs4650/) (announcements, questions, discussion)
- [Gradescope](https://www.gradescope.com/courses/569792) (homework assignments, submission and grading)
- [Tentative Course Schedule](https://docs.google.com/spreadsheets/d/18bebSK8INSUlMPV7kc7hW6wLVxWj6x3yr4QsHn8ssnY/edit#gid=0)

{% for module in site.modules %}
{{ module }}
{% endfor %}
