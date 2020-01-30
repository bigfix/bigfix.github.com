
This page is for the PDFs for the BigFix v10 Customer Tech Preview

{% for file in site.static_files %}
  {% if file.path contains "/TechPreview2020/" %}
    {% if file.extname == ".pdf" or file.extname == ".PDF" %}
* [{{ file.path }}]({{ site.baseurl }}{{ file.path }})
    {% endif %}
  {% endif %}
{% endfor %}
