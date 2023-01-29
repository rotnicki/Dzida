# Dzida

Strony???

{% for page in site.pages %}
    {% if page.path contains 'docs' %}
        {{ page.path }}
    {% endif %}
{% endfor %}
