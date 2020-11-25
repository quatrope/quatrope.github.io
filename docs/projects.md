
# Projects

{% for repository in site.github.public_repositories %}
{% if repository.topics contains "qp-toplevel"  %}
- [{{ repository.name }}]({{ repository.homepage  | default:repository.html_url }}): {{ repository.description }} ({{ repository.topics}})
{% endif %}
{% endfor %}

