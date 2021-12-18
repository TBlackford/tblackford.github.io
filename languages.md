---
layout: inner
title: 'Languages'

permalink: /languages/
pagination:
    enabled: true
---

# Languages

> I quite like languages

<div>
{% for post in site.languages %}
    <div class="wow fadeIn">
        {% include content-right.html %}
    </div>
{% endfor %}
</div>