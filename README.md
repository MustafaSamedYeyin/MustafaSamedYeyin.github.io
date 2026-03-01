# mustafasamedyeyin.github.io

{% for post in site.posts %}
<details>
  <summary>{{ post.title }}</summary>
  <p>{{ post.content }}</p>
</details>
{% endfor %}
