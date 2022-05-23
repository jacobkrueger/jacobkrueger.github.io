<details>
<summary style="cursor:pointer;"><b style="cursor:pointer;">Dissertation</b></summary>

<ol>
<li> Jacob Krüger. <a href="assets/papers/diss.pdf" target="_blank" rel="me noopener noreferrer"><b>Understanding the Re-Engineering of Variant-Rich Systems: An Empirical Work on Economics, Knowledge, Traceability, and Practices.</b></a> Otto-von-Guericke University Magdeburg, 2021. doi: 10.25673/39349 <a href="assets/papers/diss.pdf" target="_blank" rel="me noopener noreferrer"><img src="logos/pdf.png" height="12px" style="margin-inline-start: 0.75em" alt="pdf"/></a></li>
</ol>
</details>


<details>
<summary style="cursor:pointer;"><b style="cursor:pointer;">Conference & Workshop Papers</b></summary>

<ol style="counter-reset: myCounter;">
{% assign prev_year = "" %}
{% for pub in site.data.bib.proceedings %}
{% capture this_year %}{{ pub.year }}{% endcapture %}
{% if prev_year != this_year %}
{% assign prev_year = this_year %}
<li style="list-style: none; margin-inline-start: -2em; counter-increment: myCounter -1"><b>{{ this_year }}</b></li>
{% endif %}
  
<li style="margin: 5px; counter-increment: myCounter">{{ pub.author }}: <a href="assets/papers/{{ pub.id }}.pdf" target="_blank" rel="me noopener noreferrer"><b>{{ pub.title }}</b></a> {{ pub.booktitle }}, {{ pub.publisher }}, {{ pub.year }}. doi: {{ pub.doi }} <a href="assets/papers/{{ pub.id }}.pdf" target="_blank" rel="me noopener noreferrer"><img src="logos/pdf.png" height="12px" style="margin-inline-start: 0.75em" alt="pdf"/></a></li>
{% endfor %}
</ol>
</details>
