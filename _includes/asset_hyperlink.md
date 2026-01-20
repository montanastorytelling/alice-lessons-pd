{%- if assetname == nil -%}
    {%- assign assetname = include.assetname -%}
{%- endif -%}
{%- assign asseti = site.data.assets[include.assetname] -%}
{%- assign title = content.title -%}
{%- if title == nil -%}
    {%- assign title = asseti.title -%}
{%- endif -%}
[{{title}}]({{asseti.permalink | relative_url}})