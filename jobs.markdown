---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

title: Jobs
layout: default
permalink: /jobs
---

<h4 class="display-4 text-center mb-5">Jobs</h4>

<p>We have a few open positions at the moment. Still, if you do not find yours
here, you can still spontaneously apply at
<a href="mailto:hello@42hexagons.org">hello@42hexagons.org</a> with a resume /
portfolio. We always welcome talented people!</p>

<ul class="list-group list-group-flush">
  {% for job in site.jobs %}
    <li class="list-group-item">
      <a href="{{ job.url }}" class="lead">{{ job.title }}</a>
    </li>
  {% endfor %}
</ul>