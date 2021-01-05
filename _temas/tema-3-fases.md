---
  layout: default
  name: Tema 3
  visible: true
  date: 2020-11-17
  my_order: 3
---

##{{site.data.tema3.titulo}}  

{{site.data.tema3.contenido1}}

<ul>
{% for apartado in site.data.tema3.apartados%}
  <li>
    {{ apartado.dato }}: {{ apartado.contenido }}
  </li>
{% endfor %}
</ul>


