---
# You don't need to edit this file, it's empty on purpose.
# Edit theme's home layout instead if you wanna make some changes
# See: https://jekyllrb.com/docs/themes/#overriding-theme-defaults
layout: default
array: [{"nombre": "John", "apellido": "Does"},{"nombre": Max, "apellido": "Edo"}, {"nombre": "Ted", "apellido": "Jones"}]
---
<h2>Página Principal</h2>
Contenido de página principal
<br>
<h3>Ejemplo de uso de Arrays</h3>
<ul>
{% for element in page.array %}

    <li>{{ element.nombre }}  {{ element.apellido }}</li>

{% endfor %}
</ul>
