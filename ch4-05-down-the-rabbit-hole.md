---
layout: lesson
title: Giù per la tana del Bianconiglio
quote: "Vorrei quasi non essere sceso in quella tana del Bianconiglio, eppure, eppure - è piuttosto interessante, sai, questo tipo di vita."
permalink: rabbithole
order: ch4-05
toc: true
---

### Attraverso lo specchio

Dopo aver scritto le 21 lezioni, ho scritto alcuni articoli e saggi per esplorare 
più in profondità alcuni aspetti del Bitcoin.

{% include looking-glass.html hide_heading=true %}

----

### Giù per la tana del Bianconiglio

Trovate tutti il link di 'Giù per la tana del Bianconiglio' qui sotto. 
Una lista aggiornata di risorse sull'argomento Bitcoin è disponibile su
[bitcoin-resources.com][resources].

{% assign lessons_sorted = site.lessons | sort: 'order' %}
{% for lesson in lessons_sorted %}

#### [{{ lesson.title }}]({{ lesson.url }}): {{ lesson.subtitle }}

{% include rabbit-hole.html lesson=forloop.index hide_heading=true %}

{% endfor %}

----

<center>
<figure>
  <a href="https://bitcoin-resources.com"><img src="/assets/images/bitcoin-resources.png"/></a>
  <figcaption>Further resources: <a href="https://bitcoin-resources.com">bitcoin-resources.com</a></figcaption>
</figure>
</center>

<!-- Links -->
[resources]: https://bitcoin-resources.com
