
# Projects


{% for repository in site.github.public_repositories %}
<h2>{{ repository.name }}</h2>

{{ repository.description }}

<a class="btn" href='{{ repository.html_url }}'>Code</a>
<hr>
{% endfor %}
