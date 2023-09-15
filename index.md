# Seans Blog

Hello,welcome to my blog

*Welcome* to my super duper looper **blog**

Hello people of the world my name is Sean. Here we will be ytalkimg about me and my coding journey to become the best coder ever.


![me eating chicken](/assets/4.JPG)

## Recent Post
<ul>
{% for post in site.posts%}
<li>
<a href="/blog{{post.url}}">{{post.title}}</a>
</li>
{%endfor%}
</ul>