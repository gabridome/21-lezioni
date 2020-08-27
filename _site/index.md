# 21 Lezioni

Un'esplorazione sulle domande e sulle lezioni apprese nel cadere dentro la tana del Bianconiglio del Bitcoin.

Questa è la traduzione in italiano dei contenuti principali del sito 
[21lessons.com](https://21lessons.com)

[Inseguiamo il Bianconiglio](ch0-00-preface)

{% for file in site.static_files %}
{% if file.extname == ".md" %}
[{{ page.title }}]({{site.baseurl}}/{{file.basename}})
{% endif %}
{% endfor %}
