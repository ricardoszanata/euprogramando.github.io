# 👋 Bem-vindo ao Eu Programando

Aqui compartilho meus projetos, ideias e tutoriais sobre programação!

## 🧠 Projetos Recentes

<ul>
{% for repo in ricardoszanata.github.public_repositories %}
  <li>
    <a href="{{ repo.html_url }}">{{ repo.name }}</a>  
    {% if repo.description %} — {{ repo.description }}{% endif %}
  </li>
{% endfor %}
</ul>
