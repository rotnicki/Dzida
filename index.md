# Dzida

Strony???

{% for page in site.pages %}
    {% if page.path contains 'docs' %}
        {% include_relative {{ page.path }} %}
    {% endif %}
{% endfor %}
