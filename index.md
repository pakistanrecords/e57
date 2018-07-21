---

layout: text
title: Express 57
author: Jorge Rangel

---

# {{ site.title }}

*{{ site.description }}*

por: {{ page.author }} / @jarxg

---

## Cuentos

{% for item in site.cuentos %}<a href="{{ site.baseurl }}{{ item.url }}">{{ item.title }}</a><br>{% endfor %}

---

## Materiales

{% for item in site.materiales %}<a href="{{ site.baseurl }}{{ item.url }}">{{ item.title }}</a><br>{% endfor %}

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
