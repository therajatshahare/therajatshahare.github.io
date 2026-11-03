---
layout: page
title: Contact
subtitle: Get in touch
permalink: /contact/
---
I welcome conversations about literature, research collaboration, teaching and open-source work.

<ul class="contact-list">
  <li><strong>Email</strong> <a href="mailto:{{ site.author.email }}">{{ site.author.email }}</a></li>
  <li><strong>Affiliation</strong> Department of English, Rashtrasant Tukadoji Maharaj Nagpur University, Nagpur, Maharashtra, India</li>
  <li><strong>GitHub</strong> <a href="https://github.com/{{ site.author.github }}">github.com/{{ site.author.github }}</a></li>
  {% if site.author.linkedin != '' %}<li><strong>LinkedIn</strong> <a href="https://linkedin.com/in/{{ site.author.linkedin }}">linkedin.com/in/{{ site.author.linkedin }}</a></li>{% endif %}
  {% if site.author.orcid != '' %}<li><strong>ORCID</strong> <a href="https://orcid.org/{{ site.author.orcid }}">{{ site.author.orcid }}</a></li>{% endif %}
  {% if site.author.google_scholar != '' %}<li><strong>Google Scholar</strong> <a href="{{ site.author.google_scholar }}">Profile</a></li>{% endif %}
</ul>
