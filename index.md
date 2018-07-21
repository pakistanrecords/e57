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

## Materiales

{% for item in site.materiales %}<a href="{{ site.baseurl }}{{ item.url }}">{{ item.title }}</a><br>{% endfor %}

---

## Pendientes

- ¿Juntar los dos cuentos sobre la inundación?
- Escribir
	- Cuentos
	- Discografía pendiente
	- Hojas de personajes
	- Acerca de...
- Transcribir
	- Cuentos terminados
	- Discografía terminada
	- Proyecto original
	- Escenas eliminadas
