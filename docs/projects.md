
# Projects


{% for repository in site.github.public_repositories %}
<h2><a href='{{ repository.html_url }}'> {{ repository.name }}</a><h2>

> {{ repository.description }}
----
{% endfor %}
