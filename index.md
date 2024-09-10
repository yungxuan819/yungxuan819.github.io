{% for project in site.projects %}
## {{ project.title }}
**Description**: {{ project.description }}  
**Repo Link**: [{{ project.repo_link }}]({{ project.repo_link }})
{% endfor %}
