---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---
<a class="btn btn--primary" href="/files/CV(HaechangJung)ver1.pdf" download>
  Download CV (PDF)
</a>

<a href="/files/CV(HaechangJung)ver1.pdf" download
   style="
     display:inline-flex;
     align-items:center;
     gap:12px;
     padding:14px 20px;
     border:1px solid #1a1a1a;
     border-radius:8px;
     background:#ffffff;
     color:#1a1a1a;
     text-decoration:none;
     font-weight:700;
     letter-spacing:0.2px;
     box-shadow:0 8px 24px rgba(0,0,0,0.08);
     transition:transform 0.15s ease, box-shadow 0.15s ease;
   "
   onmouseover="this.style.transform='translateY(-2px)'; this.style.boxShadow='0 12px 32px rgba(0,0,0,0.12)';"
   onmouseout="this.style.transform='translateY(0)'; this.style.boxShadow='0 8px 24px rgba(0,0,0,0.08)';"
>
  <svg width="18" height="18" viewBox="0 0 24 24" fill="none"
       xmlns="http://www.w3.org/2000/svg" aria-hidden="true">
    <path d="M12 3v10" stroke="currentColor" stroke-width="2" stroke-linecap="round"/>
    <path d="M8 11l4 4 4-4" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"/>
    <path d="M4 21h16" stroke="currentColor" stroke-width="2" stroke-linecap="round"/>
  </svg>
  <span>Download CV (PDF)</span>
</a>

{% include base_path %}

Education
======
* Ph.D in Version Control Theory, GitHub University, 2018 (expected)
* M.S. in Jekyll, GitHub University, 2014
* B.S. in GitHub, GitHub University, 2012

Work experience
======
* Spring 2024: Academic Pages Collaborator
  * GitHub University
  * Duties includes: Updates and improvements to template
  * Supervisor: The Users

* Fall 2015: Research Assistant
  * GitHub University
  * Duties included: Merging pull requests
  * Supervisor: Professor Hub

* Summer 2015: Research Assistant
  * GitHub University
  * Duties included: Tagging issues
  * Supervisor: Professor Git
  
Skills
======
* Skill 1
* Skill 2
  * Sub-skill 2.1
  * Sub-skill 2.2
  * Sub-skill 2.3
* Skill 3

Publications
======
  <ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
Talks
======
  <ul>{% for post in site.talks reversed %}
    {% include archive-single-talk-cv.html  %}
  {% endfor %}</ul>
  
Teaching
======
  <ul>{% for post in site.teaching reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
Service and leadership
======
* Currently signed in to 43 different slack teams
