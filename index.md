---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

# layout: home
layout: page
---

![](img/76825961-IMG_5971-cropped2.jpeg)

# Recent Race Reports
<ul>
  {% for post in site.posts limit:3 %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a>
    </li>
  {% endfor %}
</ul>

[View more race reports](/race-reports)

# Thank you to my sponsors

[![TrackTime Track Days and Rider Training](img/sponsors/tracktime.png)](http://tracktime.bike)

    

