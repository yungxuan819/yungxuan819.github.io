<div style="display: flex; flex-wrap: wrap; gap: 20px;">
  {% for project in site.projects %}
  <div style="flex: 1; min-width: 300px;">
    <img src="{{ project.title | slugify }}.png" alt="{{ project.title }} image" style="width: 100%; height: auto;"/>
    <h2>{{ project.title }}</h2>
    <p><strong>Description:</strong> {{ project.description }}</p>
    <p><strong>Repo Link:</strong> <a href="{{ project.repo_link }}" style="word-wrap: break-word; overflow-wrap: break-word;">{{ project.repo_link }}</a></p>
  </div>
  {% endfor %}
</div>
