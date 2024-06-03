---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

# layout: home
layout: page
---

<!-- ![](img/76825961-IMG_5971-cropped2.jpeg) -->
![](/img/race-report-photos/2021/2021-gearing-up.jpg)

Chris Wilcox is a regional road racer participating in [WMRRA](https://wmrra.com) (Washington Motorcycle Road Racing Association) and [OMRRA](https://omrra.com) (Oregon Motorcycle Road Racing Association), participating in Formula 600, 600 Supersport, and 600 Superbike clases.

Chris is also a long-time volunteer of WMRRA and former executive board member (2nd VP). You can find him most race weekends at Friday night tech, making sure machinery and gear are in order for the weekend's events.

When not racing Chris works with [Track Time](https://tracktime.bike/), a premier track day provider in Washington State to grow riders in the Pacific Northwest. Reach out if you are looking to attend for 1-on-1 rider instruction.

# [Race Results](/results)

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

<table>
  <tr>
    <a href="https://shortfuseracing.com">
      <img height=200 src="/img/sponsors/short_fuse.png" />
    </a>
     <a href="https://kytamericas.com">
      <img height=100 src="/img/sponsors/kyt.png" />
    </a>
    <a href="http://tracktime.bike">
      <img height=200 src="/img/sponsors/tracktime.png" />
    </a>
    <a href="http://ctracingservices.com">
      <img height=200 src="/img/sponsors/ctr-pirelli-logo-square.jpg" />
    </a>
    <a href="http://stevensonfoto.com">
      <img height=200 src="/img/sponsors/stevensonfoto.jpg" />
    </a>
  </tr>
</table>

<!-- Mastodon Verification -->
<a rel="me" href="https://hachyderm.io/@chriswilcox"></a>
