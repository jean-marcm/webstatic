# Bienvenue

Sur mon nouveau site


<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ root_url }}{{ post.url }}">{{ post.title }}</a>
    </li>
  {% endfor %}
</ul>
