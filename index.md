# Dzida

Lista stronek:

{% for page in site.pages %}
{% if page.path contains 'docs' %}

{{ page.content }}

{% endif %}
{% endfor %}
