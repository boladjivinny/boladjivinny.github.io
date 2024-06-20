<h2 id="teaching" style="margin: 2px 0px -15px;">Teaching</h2>
<div class='teaching'>
    <ul>
    {% for class in site.data.teaching.main %}
        <li>{{ class.role }}, {{ class.title }} at <a href="{{ class.link }}">{{ class.school }}</a>, {{ class.term }}</li>
    {% endfor %}
    </ul>
</div>