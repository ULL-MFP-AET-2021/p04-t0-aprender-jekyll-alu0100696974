---
  layout: default
  name: Tarea 1
  visible: true
  date: 2020-11-17
  my_order: 1 
---

##{{site.data.tarea1.titulo}}

<ul> {% for preguntas in site.data.tarea1.preguntas%} <li>{{ preguntas }} </li> {% endfor %} </ul>
