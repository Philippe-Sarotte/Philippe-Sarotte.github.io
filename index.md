---
layout: default
title: About me
description: Personal academic page of Philippe Sarotte.
permalink: /
---

<div class="about-grid">

  <img
    class="profile-picture"
    src="{{ '/assets/images/test4.jpg' | relative_url }}"
    alt="Portrait of {{ site.author.name }}"
  >

  <div class="about-text">

    <h1>About me</h1>

    <p>
      I am a PhD student in probability at
      <strong>{{ site.author.university }}</strong>,
      affiliated with <strong>{{ site.author.laboratory }}</strong>
      under the supervision of Professor François Baccelli and
      co-supervised by Dr Nahuel Soprano-Loto.
    </p>

    <p>
      My research interests include stochastic processes, interacting particle
      systems, queueing theory, point processes, and wireless network modelling.
    </p>

    <div class="profile-links">
      <a href="{{ site.github_url }}" target="_blank" rel="noopener noreferrer">
        GitHub
      </a>

      <a href="{{ site.scholar_url }}" target="_blank" rel="noopener noreferrer">
        Google Scholar
      </a>

      <a href="{{ site.linkedin_url }}" target="_blank" rel="noopener noreferrer">
        LinkedIn
      </a>

      <a href="{{ site.orcid_url }}" target="_blank" rel="noopener noreferrer">
        ORCID
      </a>
    </div>

  </div>

</div>

---

## Research interests

- Probability theory
- Stochastic processes
- Interacting particle systems
- Queueing theory
- Information theory
- Performance evaluation of wireless networks

---

## Contact

**Email:** [{{ site.author.email }}](mailto:{{ site.author.email }})

**Institution:** {{ site.author.laboratory }}, {{ site.author.university }}

**Institution:** {{ site.author.laboratory }}, {{ site.author.university }}
