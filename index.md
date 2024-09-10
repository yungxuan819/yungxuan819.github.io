# Yung Xuan's Projects

Welcome to my personal webpage, where I showcase a collection of projects that highlight my skills and expertise in the data field.

{% for project in site.projects %}
## {{ project.title }}
**Description**: {{ project.description }}  
**Repo Link**: [{{ project.repo_link }}]({{ project.repo_link }})
{% endfor %}
