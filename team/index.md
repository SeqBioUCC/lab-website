---
title: Team
nav:
  order: 15
  tooltip: About our team
---
# {% include icon.html icon="fa-solid fa-users" %}Team
{:.center}

Lorem ipsum dolor sit amet

{% include section.html %}

{% include list.html data="members" component="portrait" filters="role: pi" %}
{% include list.html data="members" component="portrait" filters="role: ^(?!pi$)" %}

{% include section.html background="images/background.jpg" dark=true %}



<!-- PhD Students -->
{% include list.html data="members" component="portrait" filters="role: phd-*" %}

<!-- MS Students -->
{% include list.html data="members" component="portrait" filters="role: masters-*" %}

<!-- Undergrad students -->
{% include list.html data="members" component="portrait" filters="role: undergrad-*" %}
{% include section.html %}



Lorem ipsum dolor sit amet, consectetur adipiscing 

{% include section.html %}

{% capture content %}

{% include figure.html image="images/photo.jpg" %}
{% include figure.html image="images/photo.jpg" %}
{% include figure.html image="images/photo.jpg" %}
{% include figure.html image="images/photo.jpg" %}
{% endcapture %}



<!-- Social Photo -->
## Team Gathering
{:.center}

{% capture content %}
![image]({{ "/images/socials/dinner-2023.12.06.jpeg" | relative_url }})

![image]({{ "/images/socials/BMI_party-2023.12.07/decoration-wall.jpg" | relative_url }})

![image]({{ "/images/socials/CEP-2023.12.08/lunch.png" | relative_url }})

![image]({{ "/images/socials/BMI_party-2023.12.07/soheil-sepideh.jpg" | relative_url }})

![image]({{ "/images/socials/CEP-2023.12.08/cep-board.png" | relative_url }})

![image]({{ "/images/socials/BMI_party-2023.12.07/tv.jpg" | relative_url }})

{% endcapture %}

{% include grid.html style="square" content=content %}
