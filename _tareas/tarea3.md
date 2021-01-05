---
  layout: default
  name: Tarea 3
  visible: false
  date: 2020-11-18
  my_order: 3
---

##{{site.data.tarea3.titulo}}

<ul> {% for preguntas in site.data.tarea3.preguntas%} <li>{{ preguntas }} </li> {% endfor %} </ul>