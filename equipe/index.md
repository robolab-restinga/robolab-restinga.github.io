---
layout: default
---

# Equipe | Integrantes

O Laboratório de Robótica do Instituto Federal do RS - Campus Restinga está sempre presente em diversas competições de Robótica.

<!-- LOOP MOSTRANDO CADA INTEGRANTE, COM NOME E FOTO -->

<ul class="list-group list-group-flush">
{% for person in site.data.integrantes %}
    <li class="list-group-item">
        <h2>{{ person.name }}</h2>
        
        - {{ person.position }}
    </li>
{% endfor %}
</ul>
