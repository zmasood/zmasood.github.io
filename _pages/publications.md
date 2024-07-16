---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

**2024**

**Almakhles, Dhafer** and Mahmoud Abdelrahim. Event-triggered dynamic quantization for nonlinear systems with one-bit data transmission. IEEE Transactions on Automatic Control, 2024

**Almakhles, Dhafer** and Mahmoud Abdelrahim. A novel one-bit dynamic quantizer for event-triggered control systems. Information Sciences, page 120113, 2024

**Almakhles, Dhafer** and Mahmoud Abdelrahim. Asynchronous dynamic quantization for nonlinear systems with one-bit data transmission. Systems & Control Letters, 181:105630, 2024


{% if site.author.googlescholar %}
  <div class="wordwrap">You can also find my articles on <a href="{{site.author.googlescholar}}">my Google Scholar profile</a>.</div>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
