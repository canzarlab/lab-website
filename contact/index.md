---
title: Contact
nav:
  order: 5
  tooltip: Email, address, and location
---

# {% include icon.html icon="fa-regular fa-envelope" %}Contact

We are part of the faculty of informatics and data science (FIDS) at the University of Regensburg (UR). The lab is located on the 4th floor of Bajuwarenstr. 4, in 93053 Regensburg, Germany.

{%
  include button.html
  type="email"
  text="jane@smith.com"
  link="jane@smith.com"
%}
{%
  include button.html
  type="phone"
  text="(555) 867-5309"
  link="+1-555-867-5309"
%}
{%
  include button.html
  type="address"
  tooltip="Our location on Google Maps for easy navigation"
  link="https://maps.app.goo.gl/1N5yfUMMohZAyg5v9"
%}

{% include section.html %}

{% capture col1 %}

{%
  include figure.html
  image="images/ur_fruehling_weich.jpg"
  caption="FIDS at UR"
%}

{% endcapture %}

{% capture col2 %}

{%
  include figure.html
  image="images/2019_regensburg_dagan.jpg"
  caption="Lorem ipsum"
%}

{% endcapture %}

{% include cols.html col1=col1 col2=col2 %}

