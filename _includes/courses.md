<h2 id="teaching" style="margin: 2px 0px -15px;">Teaching</h2>
<ul>
{% for class in site.data.main %}
    <li>{{ class.role }}, {{ class.title }} at <a href="{{ class.link }}">{{ class.school }}, {{ class.term }}</li>
</ul>
