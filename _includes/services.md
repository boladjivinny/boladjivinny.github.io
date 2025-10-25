<h2 id="services">Service</h2>

<div class="services">
  <h4 style="margin:0 10px 0;">Technical Program Committees</h4>
  <ul style="margin: 0 0 5px;">
    {% for entry in site.data.services.tpc %}
      <li><a href="{{ entry.link }}"><autocolor>{{ entry.conference }}</autocolor></a> ({{ entry.conference_short }}) {{ entry.years }}</li>
    {% endfor %}
  </ul>
  <h4 style="margin:0 10px 0;">Artifact Evaluation Committees</h4>
  <ul style="margin: 0 0 5px;">
    {% for entry in site.data.services.aec %}
      <li><a href="{{ entry.link }}"><autocolor>{{ entry.conference }}</autocolor></a> ({{ entry.conference_short }}) {{ entry.years }}</li>
    {% endfor %}
  </ul>
</div>
