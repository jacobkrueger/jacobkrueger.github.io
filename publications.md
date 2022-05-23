{% assign pubCounter = 3 %}
<details>
<summary style="cursor:pointer;"><b style="cursor:pointer;">Dissertation</b></summary>

<ol start="{{ pubCounter }}">
{% assign pubCounter = pubCounter+1 %}
<li> Jacob Krüger. <a href="assets/papers/diss.pdf" target="_blank" rel="me noopener noreferrer"><b>Understanding the Re-Engineering of Variant-Rich Systems: An Empirical Work on Economics, Knowledge, Traceability, and Practices.</b></a> Otto-von-Guericke University Magdeburg, 2021. doi: 10.25673/39349 <a href="assets/papers/diss.pdf" target="_blank" rel="me noopener noreferrer"><img src="logos/pdf.png" height="12px" style="margin-inline-start: 0.75em" alt="pdf"/></a></li>
</ol>
</details>


<details>
<summary style="cursor:pointer;"><b style="cursor:pointer;">Conference & Workshop Papers</b></summary>

{% assign prev_year = "" %}
{% for pub in site.data.bib.proceedings %}
{% capture this_year %}{{ pub.year }}{% endcapture %}
{% if prev_year != this_year %}
{% if prev_year != "" %}
</ol>
{% endif %}
{% assign prev_year = this_year %}
<b>{{ this_year }}</b>
<ol start="{{ pubCounter }}">
{% endif %}
  
<li style="margin: 5px;">{{ pub.author }}: <a href="assets/papers/{{ pub.id }}.pdf" target="_blank" rel="me noopener noreferrer"><b>{{ pub.title }}</b></a> {{ pub.booktitle }}, {{ pub.publisher }}, {{ pub.year }}. doi: {{ pub.doi }} <a href="assets/papers/{{ pub.id }}.pdf" target="_blank" rel="me noopener noreferrer"><img src="logos/pdf.png" height="12px" style="margin-inline-start: 0.75em" alt="pdf"/></a></li>
{% assign pubCounter = pubCounter+1 %}
{% endfor %}
</ol>
</details>
