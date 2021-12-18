---
layout: inner
title: 'Languages'
permalink: /languages/
pagination:
    enabled: true
---

# Languages

<div>
{% for post in site.languages %}
    <div class="wow fadeIn">
        {% include language-post-item.html %}
    </div>
{% endfor %}
</div>