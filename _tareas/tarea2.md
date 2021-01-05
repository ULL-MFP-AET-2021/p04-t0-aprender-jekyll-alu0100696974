---
  layout: default
  name: Tarea 2
  visible: true
  date: 2020-11-16
  my_order: 2
---

##{{site.data.tarea2.titulo}}

<ul> {% for preguntas in site.data.tarea2.preguntas%} <li>{{ preguntas }} </li> {% endfor %} </ul>