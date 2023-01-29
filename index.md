# Dzida

Lista stron:

{% for page in site.pages %}
{% if page.path contains 'docs' %}

## {{ page.title }}

{% endif %}
{% endfor %}
