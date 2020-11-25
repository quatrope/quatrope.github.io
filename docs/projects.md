
# Projects


{% for repository in site.github.public_repositories %}
<h2>{{ repository.name }} <a class="btn" href='{{ repository.html_url }}'>Code</a></h2>

{{ repository.description }}

---
{% endfor %}
