---
title: Contact
nav:
  order: 5
  tooltip: Email, address, and location
---

# {% include icon.html icon="fa-regular fa-envelope" %}Contact

Our lab is part of the Department of Materials Science and Engineering at University of Virginia. Come and visit us at our location in Wilsdorf Hall, on the beautiful UVA grounds in Charlottesville, Virginia.

{%
  include button.html
  type="email"
  text="Email"
  link="fqw3ss@virginia.edu"
%}
{%
  include button.html
  type="address"
  tooltip="Our location on Google Maps for easy navigation"
  link="https://maps.app.goo.gl/cgpScvo15gmDoRgSA"
%}

{% include section.html %}

{% capture col1 %}

{%
  include figure.html
  image="images/contact-1.jpg"
%}

{% endcapture %}

{% capture col2 %}

{%
  include figure.html
  image="images/contact-2.jpg"
%}

{% endcapture %}

{% capture col3 %}

{%
  include figure.html
  image="images/contact-3.jpg"
%}

{% endcapture %}

{% include cols.html col1=col1 col2=col2 col3=col3%}

{% include section.html dark=true %}
