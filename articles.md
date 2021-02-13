---
layout: default
title: "TBlackford"
active: "articles"
---

## Articles

<ul>
    {% for article in site.articles %}
        <li>
            <a href="{{ article.url }}">{{ article.title }}</a>
        </li>
    {% else %}
        <p>No Articles</p>
    {% endfor %}
</ul>
