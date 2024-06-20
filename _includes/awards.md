<h2 id="awards">Awards</h2>
<ul>
    {% for award in site.data.awards.main %}
    <li><strong><a href="{{ award.ref }}">{{ award.title }}</a></strong>, {{ award.org }}</li>
    {% endfor %}
</ul>