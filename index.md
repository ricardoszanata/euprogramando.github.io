# 👋 Bem-vindo ao Eu Programando

Aqui compartilho meus projetos, ideias e tutoriais sobre programação!

## 🧠 Projetos Recentes

<ul>
{% for repo in github.com/ricardoszanata?tab=repositories&q=&type=public&language=&sort= %}
  <li>
    <a href="{{ repo.html_url }}">{{ repo.name }}</a>  
    {% if repo.description %} — {{ repo.description }}{% endif %}
  </li>
{% endfor %}
</ul>
