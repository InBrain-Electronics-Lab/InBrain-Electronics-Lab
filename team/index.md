---
title: Our Team
nav:
  order: 3
  tooltip: About our lab
---

# {% include icon.html icon="fa-solid fa-users" %}A small but mighty team makes up the InBrain Electronics Lab!

{% include section.html %}

{% include list.html data="ilke-uguz.md" component="portrait" filter="role == 'pi'" %}

{% include section.html background="images/background.jpg" dark=true %}
{% include figure.html image="images/Ilke.png" %}


{% include section.html %}

{% include list.html data="jie-dai.md" component="portrait" filter="role != 'PhD Student'" %}
{% include section.html background="images/background.jpg" dark=true %}
{% include figure.html image="images/Jie.png" %}


{% include section.html %}
{% include list.html data="sara-bender-bier.md" component="portrait" filter="role != 'PhD Student'" %}
{% include figure.html image="images/Sara.jpg" %}


{% capture content %}

{% include figure.html image="images/photo.jpg" %}

{% endcapture %}

{% include grid.html style="square" content=content %}
