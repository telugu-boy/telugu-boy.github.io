---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: default
---
"

ight bruh

ya just be dat ohncal

<ul class="post-list">
{%- for post in site.posts -%}
<li>
  <article>
    <span>
    
      <a href="{{ post.url }}">
        {{ post.title }}
      </a>
    
    <time datetime="{{ post.date | date: "%Y-%m-%d" }}">{{ post.date | date_to_long_string }}</time>
    </span>
  </article>
</li>
{%- endfor -%}
</ul>