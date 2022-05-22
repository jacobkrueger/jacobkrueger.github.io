## Dissertation

<ol>
<li> Jacob Krüger. Understanding the Re-Engineering of Variant-Rich Systems: An Empirical Work on Economics, Knowledge, Traceability, and Practices. Otto-von-Guericke University Magdeburg, 2021. doi: 10.25673/39349</li>
</ol>
  
## Conference & Workshop Papers

<ol>
{% for pub in site.data.bib.proceedings %}
<li>{{ pub.author }}: [{{ pub.title }}](assets/papers/{{ pub.id }}.pdf) {{ pub.booktitle }}, {{ pub.publisher }}, {{ pub.year }}. doi: {{ pub.doi }} <a href="assets/papers/{{ pub.id }}.pdf" target="_blank" rel="me noopener noreferrer"><img src="logos/pdf.png" height="24px" style="margin-inline-start: 0.75em" alt="pdf"/></a>
  </li>
{% endfor %}
</ol>
