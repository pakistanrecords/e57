---

layout: text
title: Express 57
description: Un libro de cuentos open-source acerca de Pakistán Records
author: Jorge Rangel

---

# {{ page.title }}

*{{ page.description }}*

por: {{ page.author }}

---

## Cuentos

{% for item in site.cuentos %}<a href="{{ site.baseurl }}{{ item.url }}">{{ item.title }}</a> ({{ item.status }})<br>{% endfor %}

---

## Extras

{% for item in site.extras %}<a href="{{ site.baseurl }}{{ item.url }}">{{ item.title }}</a><br>{% endfor %}
