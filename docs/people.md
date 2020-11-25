
# People

{% for person in site.people %}
## {{ person.name }}

> {{ person.description }}

[More info]({{ person.link }})
{% endfor %}

