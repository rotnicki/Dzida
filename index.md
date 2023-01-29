# Lista

{% assign pages = site.pages %}
{% for page in pages %}
    {{page.content}}
{% endfor %}
