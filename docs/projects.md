
# Projects

{% for prj in site.quatrope_toplevel_projects %}
- [{{ prj.name }}]({{ prj.link }}): {{ prj.description }}
{% endfor %}

