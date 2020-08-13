# Julien's Website

# My Interests:
I'm interested in education.
I'm also learning to code in order to change career.

# My Blog
This is my journey on GitHub.com.
<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}"> {{ post.title }} </a>
    </li>
  {% endfor %}
</ul>

# Get in Touch
<ul>
<li><a href="https://github.com/{{site.github_username}}">GitHub</a></li>
<li><a href="https://t.me/{{site.telegram_username}}">Telegram</a></li>
</ul>

<ul>
<li><a href="https://daembius.github.io/HelloWorld?">Hello World Project</a> </li>
</ul>
