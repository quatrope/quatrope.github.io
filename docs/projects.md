
# Projects


{% for repository in site.github.public_repositories %}
  <a href='{{ repository.html_url }}'>
    {{ repository }}
  </a>
{% endfor %}
