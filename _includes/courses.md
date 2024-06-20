<h2 id="teaching">Teaching</h2>
<div class='teaching'>
    <ul>
    {% for class in site.data.teaching.main %}
        <li>{{ class.role }}, <strong>{{ class.title }}</strong> at <a href="{{ class.link }}">{{ class.school }}</a>, {{ class.term }}</li>
    {% endfor %}
    </ul>
</div>