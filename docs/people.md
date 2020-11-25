
# People

{% for person in site.people %}
## {{ person.name }}
<span class="avatar"> 
![Avatar]({{ person.avatar }})
<span>
> {{ person.description }}

[More info]({{ person.link }})
{% endfor %}

