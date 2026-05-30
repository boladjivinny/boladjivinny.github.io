<h2 id="publications" style="margin: 2px 0px -15px;">Peer-Reviewed Papers</h2>

<div class="publications">
<ol class="bibliography">

{% for link in site.data.publications.main %}

<li>
<div class="pub-row">
  <div class="col-sm-12" style="position: relative;padding-right: 15px;padding-left: 20px;">
      <div class="title"><a href="{{ link.pdf }}">{{ link.title }}</a></div>
      <div class="author">{{ link.authors }}</div>
      <div class="periodical"><em>{{ link.conference }}</em>
      </div>
    <div class="links">
      {% if link.pdf %} 
      <a href="{{ link.pdf }}" class="btn btn-sm z-depth-0" role="button" target="_blank" style="font-size:12px;">PDF</a>
      {% endif %}
      {% if link.artifacts %} 
      <a href="{{ link.artifacts }}" class="btn btn-sm z-depth-0" role="button" target="_blank" style="font-size:12px;">Artifacts</a>
      {% endif %}
      {% if link.page %} 
      <a href="{{ link.page }}" class="btn btn-sm z-depth-0" role="button" target="_blank" style="font-size:12px;">Project Page</a>
      {% endif %}
      {% if link.bibtex %} 
      <a class="btn btn-sm z-depth-0" style="font-size:12px;" onclick="toggleBibtex(this)">BibTex</a>
      <div class="bibtex-content" style="display:none; margin-top: 10px; padding: 10px; background-color: #f5f5f5; border: 1px solid #ddd; border-radius: 4px; max-height: 200px; overflow-y: auto; font-family: monospace; font-size: 11px; white-space: pre-wrap; word-break: break-word;">{{ link.bibtex }}</div>
      {% endif %}
      {% if link.notes %} 
      <strong> <i style="color:#e74d3c">{{ link.notes }}</i></strong>
      {% endif %}
      {% if link.others %} 
      {{ link.others }}
      {% endif %}
    </div>
  </div>
</div>
</li>

<br>

{% endfor %}

</ol>
</div>

