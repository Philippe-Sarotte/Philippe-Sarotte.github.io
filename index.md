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
      <strong>{{ site.author.university }}</strong>, affiliated with
      <strong>{{ site.author.laboratory }}</strong>. My PhD is supervised by
      Professor François Baccelli and co-supervised by Dr Nahuel Soprano-Loto.
    </p>

    <p>
      My research focuses on stochastic processes, interacting particle
      systems, queueing theory, point processes, and wireless network modeling.
    </p>

    <div class="profile-links">
      <a href="{{ site.github_url }}" target="_blank" rel="noopener noreferrer">GitHub</a>
      <a href="{{ site.scholar_url }}" target="_blank" rel="noopener noreferrer">Google Scholar</a>
      <a href="{{ site.linkedin_url }}" target="_blank" rel="noopener noreferrer">LinkedIn</a>
      <a href="{{ site.orcid_url }}" target="_blank" rel="noopener noreferrer">ORCID</a>
    </div>
  </div>
</div>

<hr>

<h2>Research interests</h2>

<ul>
  <li>Probability theory</li>
  <li>Stochastic processes</li>
  <li>Interacting particle systems</li>
  <li>Queueing theory</li>
  <li>Information theory</li>
  <li>Performance evaluation of wireless networks</li>
</ul>

<hr>

<h2>Contact</h2>

<p><strong>Email:</strong> <a href="mailto:{{ site.author.email }}">{{ site.author.email }}</a></p>

<p><strong>Institution:</strong> {{ site.author.laboratory }}, {{ site.author.university }}</p>

