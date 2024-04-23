---
title: Contact
nav:
  order: 5
  tooltip: Email, address, and location
---

# {% include icon.html icon="fa-regular fa-envelope" %}Contact

We are part of the Faculty of Informatics and Data Science (FIDS) at the University of Regensburg (UR). The lab is located on the 4th floor at

###{% include icon.html icon="fa-regular fa-mail-bulk" %} Bajuwarenstr. 4,
93053 Regensburg, Germany
{:.center}

{%
  include button.html
  type="email"
  text="Email PI"
  link="stefan.canzar@ur.de"
%}
{%
  include button.html
  type="email"
  text="Email Secretary's Office"
  link="sekretariat.canzar@ur.de"
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
  caption="Campus University of Regensburg - by UR/Matthias Weich"
%}

{% endcapture %}

{% capture col2 %}

{%
  include figure.html
  image="images/2020_regensburg_deli.jpg"
  caption="Regensburg's Old City - by UR/Markus Deli"
%}

{% endcapture %}

{% include cols.html col1=col1 col2=col2 %}

