# Dzida

Lista stron:

{% for page in site.pages %}
  {% if page.path contains 'docs' %}
    <ul>
* {{ page.title }}</li>
    </ul>
  {% endif %}
{% endfor %}
