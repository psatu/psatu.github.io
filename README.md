## PSATU

{% for repository in site.github.public_repositories %}
  * [{{ repository.name }}]({{ repository.html_url }}) <sub>{{ repository }}</sub>
{% endfor %}
