---
layout: single
author_profile: false
title: Contact Us
description: "Mamakden Contact, email, phone, Instagram, IG, whatsapp, WA "
permalink: /contact/
header:
    #image: "/images/container-panoramic.1.jpg"
---
![full]({{site.banner}}){: .full}

<div> 
<ul class="social-icons" style="list-style: none;">
{% for link in site.footer.links %}
    {% if link.label and link.url %}
    <li><a href="{{ link.url }}" rel="nofollow noopener noreferrer" STYLE="text-decoration: none"><i class="{{ link.icon | default: 'fas fa-link' }}" aria-hidden="true"></i> {{ link.label2 }}</a></li>
    {% endif %}
{% endfor %}
</ul>
</div>