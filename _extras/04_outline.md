---

layout: text
title: Outline

---

# {{ page.title }}

{% for item in site.cuentos %}

---

## [{{ item.title }}]({{ site.baseurl }}{{ item.url }})

### Status

{{ item.status }}

### Año

{{ item.year }}

### Punto de vista

{{ item.pov }}

### Sinopsis

{{ item.synopsis }}

{% endfor %}