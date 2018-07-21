---

layout: text
title: Express 57
author: Jorge Rangel

---

{{ site.url }}

# {{ site.title }}

*{{ site.description }}*

por: {{ page.author }} / @jarxg

---

## Cuentos

{% for item in site.cuentos %}<a href="{{ site.url }}/{{ item.url }}">{{ item.title }}</a><br>{% endfor %}

---

## Materiales

{% for item in site.materiales %}<a href="{{ item.url }}">{{ item.title }}</a><br>{% endfor %}

---

## Pendientes

- Escribir
	- Cuentos
	- Discografía pendiente
	- Hojas de personajes
	- Acerca de...

- Transcribir
	- Cuentos terminados
	- Discografía terminada
	- Proyecto original
