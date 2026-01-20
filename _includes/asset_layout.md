{%- if assetlayout == nil -%}
    {%- assign assetlayout = include.assetlayout -%}
{%- endif -%}
{%- for asset in assetlayout -%}
    {%- assign assetlayout = nil-%}
    {%- assign assetname = nil -%}
    {%- assign assetobject = nil -%}


    {%- for assetO in asset -%}
        {%- assign assetname = assetO[0] -%}
        {%- assign assetobject = assetO[1] -%}
    {%- endfor -%}
    {%- if assetobject == nil -%}
        {%- assign assetobject = asset -%}
    {%- endif -%}
    {%- if assetname == nil -%}
        {%- assign assetname = asset -%}
    {%- endif -%}

    {%- assign title = nil -%}
    {%- assign desc = nil -%}
    {%- if assetobject.title != nil -%}
        {%- assign title = assetobject.title -%}
    {%- endif -%}
    {%- if assetobject.desc != nil -%}
        {%- assign desc = assetobject.desc -%}
    {%- endif -%}

    {%- include asset_print.md assetname=assetname -%}
    {%- if assetobject.include != nil -%}
        {%- assign mdindent = mdindent | prepend: "  " -%}
        {%- assign assetlayout = assetobject.include -%}
        {%- include asset_layout.md -%}
        {%- assign mdindent = test | pop -%}
    {%- endif -%}
{%- endfor -%}