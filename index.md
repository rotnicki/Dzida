# Dzida

Strony???

{% for page in site.pages %}
    {% if page.dir contains 'docs' %}
        {% include_relative {{ page.path }} %}
    {% endif %}
{% endfor %}
