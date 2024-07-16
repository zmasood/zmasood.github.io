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

**2023**

Neeraj Priyadarshi, MS Bhaskar, and **Almakhles, Dhafer**. A novel hybrid woade algorithm based mppt employed wecs for water pumping applications: Practical realization. IEEE Transactions on Industrial
Electronics, 2023

Prabhakaran Koothu Kesavan, Umashankar Subramaniam, and Almakhles, Dhafer J. Reduced switch inverter fed sensorless pmsm drive with multistage mras speed estimator based on stator flux and electromagnetic torque. IEEE Transactions on Transportation Electrification, 2023

Mahmoud Abdelrahim and **Almakhles, Dhafer**. Observer-based control of inductive wireless power transfer system using genetic algorithm. Processes, 11(6):1859, 2023

Mahmoud Abdelrahim and **Almakhles, Dhafer**. Synthesis of state/output feedback event-triggered controllers for load frequency regulation in hybrid wind–diesel power systems.
Applied Sciences, 13(17):9652, 2023


{% if site.author.googlescholar %}
  <div class="wordwrap">You can also find my articles on <a href="{{site.author.googlescholar}}">my Google Scholar profile</a>.</div>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
