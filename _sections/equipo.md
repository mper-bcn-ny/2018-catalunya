---
title: Equipo
icon: fa-users
order: 100
---

<style>

ul.nombres {
    list-style: none;
}

ul.nombres li {

    display: inline-block; 
    padding-left: 1em; 
    white-space: nowrap;

}

</style>

<iframe id="datawrapper-chart-CdGSv" src="//datawrapper.dwcdn.net/CdGSv/1/" scrolling="no" frameborder="0" allowtransparency="true" style="width: 0; min-width: 100% !important;" height="400"></iframe><script type="text/javascript">if("undefined"==typeof window.datawrapper)window.datawrapper={};window.datawrapper["CdGSv"]={},window.datawrapper["CdGSv"].embedDeltas={"100":400.003472,"200":400.003472,"300":400.003472,"400":400.003472,"500":400.003472,"700":400.003472,"800":400.003472,"900":400.003472,"1000":400.003472},window.datawrapper["CdGSv"].iframe=document.getElementById("datawrapper-chart-CdGSv"),window.datawrapper["CdGSv"].iframe.style.height=window.datawrapper["CdGSv"].embedDeltas[Math.min(1e3,Math.max(100*Math.floor(window.datawrapper["CdGSv"].iframe.offsetWidth/100),100))]+"px",window.addEventListener("message",function(a){if("undefined"!=typeof a.data["datawrapper-height"])for(var b in a.data["datawrapper-height"])if("CdGSv"==b)window.datawrapper["CdGSv"].iframe.style.height=a.data["datawrapper-height"][b]+"px"});</script>

{%- assign _pages = site.html_pages | where_exp: "item", "item.dir == '/nosotros/'" -%}
<ul class="nombres">
      {%- for _page in _pages -%}
        {%- assign _title = _page.title | default: _page.layout -%}
        {%- assign _slug = _title | slugify -%}
        {%- assign _icon = _page.icon | default: 'fa-caret-right' -%}
          <li><a href="{{- _page.url | absolute_url -}}" id="{{- _slug -}}-link">
            <span>{{- _title -}}</span>
          </a></li>
      {%- endfor -%}
</ul>

