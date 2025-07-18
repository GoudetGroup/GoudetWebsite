---
title: Contact
nav:
  order: 4
  tooltip: Email, address, and location
---

# {% include icon.html icon="fa-regular fa-envelope" %}Contact

Our lab is currently looking for XXX and YYY - Feel free to contact us for any requests! Personal e-mail address are also available in the [Team](https://goudetgroup.github.io/GoudetWebsite/team/) section.

{%
  include button.html
  type="email"
  text="jerome.goudet@unil.ch"
  link="jerome.goudet@unil.ch"
%}
{%
  include button.html
  type="address"
  tooltip="Our location on Google Maps for easy navigation"
  link="https://maps.app.goo.gl/K3GdYcG1RCYYkw2m8"
%}

{% include section.html %}

{% capture content %}
  {% include figure.html image="../images/DEE_Logo.png" alt="DEE Logo" link="https://www.unil.ch/dee/en/home.html" %}
  {% include figure.html image="../images/UNIL_Logo.png" alt="UNIL Logo" link="[https://www.unil.ch](https://www.unil.ch/unil/fr/home.html)" %}
{% endcapture %}

{% include grid.html style="square two-cols" content=content %}
