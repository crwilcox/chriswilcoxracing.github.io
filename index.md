---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

# layout: home
layout: page
---

<!-- ![](img/76825961-IMG_5971-cropped2.jpeg) -->
![](/img/race-report-photos/2021/2021-gearing-up.jpg)

Chris Wilcox is a regional road racer participating in [WMRRA](https://wmrra.com) (Washington Motorcycle Road Racing Association) and [OMRRA](https://omrra.com) (Oregon Motorcycle Road Racing Association), participating in Formula 600, 600 Supersport, and 600 Superbike classes.

Chris is also a long-time volunteer of WMRRA and former executive board member (2nd VP). You can find him most race weekends at Friday night tech, making sure machinery and gear are in order for the weekend's events.

When not racing Chris works with [Track Time](https://tracktime.bike/), a premier track day provider in Washington State owned and operated by [Ken Hill](http://khcoaching.com/) and Alan Schwen, to grow riders in the Pacific Northwest.


# Recent Race Reports
<ul>
  {% for post in site.posts limit:10 %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a>
    </li>
  {% endfor %}
</ul>

[View more race reports](/race-reports)

# Thank you to my sponsors

[![TrackTime Track Days and Rider Training](img/sponsors/tracktime.png)](http://tracktime.bike)
    

