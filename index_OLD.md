# Dzidada

Lista stron:

{% for page in site.pages %}
    {% if page.path contains 'docs' %}
        <p>{{ page.title }}</p>
    {% endif %}
{% endfor %}
