---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

# layout: home
layout: page
---
![](/img/2025-RS660-T15-Hero.JPG)

Chris Wilcox is a regional road racer participating in [WMRRA](https://wmrra.com) (Washington Motorcycle Road Racing Association) and [OMRRA](https://omrra.com) (Oregon Motorcycle Road Racing Association), participating in Twins classes aboard an Aprilia RS 660. Chris has previously competed on Yamaha R6s in Formula 600, 600 Supersport, and 600 Superbike classes.

Chris is also a long-time volunteer of WMRRA. He is currently on the WMRRA Board of Directors and previously served as 2nd VP on the executive board. You can find him most race weekends at Friday night tech, making sure machinery and gear are in order for the weekend's events.

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
     <a href="http://stevensonfoto.com">
      <img height=200 src="/img/sponsors/stevensonfoto.jpg" />
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
    <a href="http://woodcraft-cfm.com">
      <img height=200 src="/img/sponsors/woodcraft.jpg" />
    </a>
    <a href="https://shortcircuitracing.com">
      <img height=200 src="/img/sponsors/no-disassemble.png" />
    </a>
    <!-- <a href="https://shortfuseracing.com">
      <img height=200 src="/img/sponsors/short_fuse.png" />
    </a> -->
  </tr>
</table>

<!-- Mastodon Verification -->
<a rel="me" href="https://hachyderm.io/@chriswilcox"></a>
