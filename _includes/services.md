<h2 id="services" style="margin: 2px 0px -15px;">Service</h2>

<div class="services">
  <h4 style="margin:0 10px 0;">Artifact Evaluation Committees</h4>
  <ul style="margin: 0 0 5px;">
    {% for entry in site.data.services.aec %}
      <li><a href="{{ entry.link }}"><autocolor>{{ entry.conference }}</autocolor></a> ({{ entry.conference_short }}) {{ entry.years }}
    {% endfor %}
  </ul>
</div>