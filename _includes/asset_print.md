{% assign asseti = site.data.assets[include.assetname] -%}
{%- if title == nil -%}
    {%- assign title = asseti.title -%}
{%- endif -%}
{%- if desc == nil -%}
    {%- assign desc = asseti.desc -%}
{%- endif -%}
{% comment %}{% endcomment %}
{{mdindent}}- {% include asset_hyperlink.md %}
{%- if desc != nil -%}
{% comment %}{% endcomment %}
{{mdindent}}  - {{desc}}
{%- endif -%}