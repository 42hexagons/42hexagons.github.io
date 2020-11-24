---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

title: Jobs
layout: default
---

<h4 class="display-4 text-center">Jobs</h4>

<ul>
  {% for job in site.jobs %}
    <li>
      <a href="{{ job.url }}">{{ job.title }}</a>
    </li>
  {% endfor %}
</ul>