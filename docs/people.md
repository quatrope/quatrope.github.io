
# People

{% for person in site.people %}
## {{ person.name }}
<span class="avatar"> 
![Avatar]({{ person.avatar }})
<span>
> {{ person.description }}

[More info]({{ person.link }})
{% endfor %}



## Afiliaciones

-   [Centro Franco Argentino de Ciencias de la Información y de Sistemas (CIFASIS-UNR)](https://www.cifasis-conicet.gov.ar/)
-   [Instituto de Astronomía Teórica y Experimental (IATE-OAC-UNC)](http://iate.oac.uncor.edu/)
-   [Department of Physics, Duke University](https://phy.duke.edu/)
