
# Projects


<ul>
{% for repository in site.github.public_repositories %}
<li>
<a class="btn" href='{{ repository.html_url }}'>{{ repository.name }}<a>: {{ repository.description }}
</li>

{% endfor %}
<ul>
