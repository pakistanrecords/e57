---

layout: default
title: Express 57
description: Un libro de cuentos open-source acerca de Pakistán Records
author: Jorge Rangel

---

# {{ page.title }}

*{{ page.description }}*

por: {{ page.author }}

Hola. Esta es la página donde compartiré el proceso de escritura de un libro de cuentos en el que de alguna u otra forma he estado trabajando durante años. Los cuentos siguen la peripecias de un grupo de músicos y artistas de diversa índole que un buen día decidieron que era buena idea fundar una disquera en medio del desierto coahuilense: Pakistán Records. Otros cuentos no hablan directamente de la disquera pero se relacionan íntimamente con ella.  

Quiero aclarar que este sitio NO es el libro, sino una ventana a mi proceso de escritura. Mi intención es eventualmente publicar este libro de manera más "tradicional", guarever dat mins.

---

## Cuentos

{% for item in site.cuentos %}<a href="{{ site.baseurl }}{{ item.url }}">{{ item.title }}</a> ({{ item.status }})<br>{% endfor %}

---

## Extras

{% for item in site.extras %}<a href="{{ site.baseurl }}{{ item.url }}">{{ item.title }}</a><br>{% endfor %}
