
# Projects

{% for repository in site.github.public_repositories %}
- [{{ repository.name }}]({{ repository.homepage  | default:repository.html_url }}): {{ repository.description }} ({{ repository.topics}})
{% endfor %}

