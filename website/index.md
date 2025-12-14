---
layout: default
title: Resume
permalink: /
---

<link rel="stylesheet" href="{{ '/assets/css/profile.css' | relative_url }}">

{% capture header_md %}
# Your Name

_Your Title • Key Skills/Focus Areas • Short Tagline_

- Email: [you@example.com](mailto:you@example.com)  
- GitHub: [github.com/your-handle](https://github.com/your-handle)  
- Certifications: see the [Certifications](/badges/) page
  
[![Built with BadgeBox](https://img.shields.io/badge/built%20with-BadgeBox-blue)](https://github.com/binbashburns/badgebox-resume)
{% endcapture %}

<div class="hero">
  <div class="hero-text">{{ header_md | markdownify }}</div>
  <img class="avatar" src="{{ '/assets/img/profile.png' | relative_url }}" alt="Your Name" loading="lazy" />
  <!-- Replace the image at assets/img/profile.png with your own headshot -->
  <!-- Or update the path above to point at a different image -->
 </div>

---

## About me

One or two concise paragraphs that describe your background, strengths, and interests.  
Common topics: cloud/platform engineering, application development, security, data, DevOps, SRE, etc. Mention the tools and platforms you’re comfortable with (e.g., AWS/Azure/GCP, Kubernetes, Terraform, GitHub Actions) and what kinds of problems you like to solve.

Example: “I’m a platform engineer focused on secure software delivery and scalable infrastructure. I enjoy building declarative platforms with IaC and GitOps, and partnering with teams to ship reliable services.”

---

## Experience

### Company Name – Role/Title
_Start – End_ • [company.com](https://example.com)
- Impact-focused bullet using action + outcome (what changed, how you measured it).
- Technologies, scale, or constraints that show depth (Kubernetes, Terraform, CI/CD, etc.).
- Cross-team collaboration, leadership, or ownership highlights.

### Company Name – Role/Title
_Start – End_ • [company.com](https://example.com)
- …
- …

### Company Name – Role/Title
_Start – End_ • [company.com](https://example.com)
- …
- …

---

## Education

### University or Program – Degree / Certificate
_Dates_
- Highlights: GPA, honors, focus areas, clubs, capstone, relevant coursework.

### Additional Training or Bootcamps (optional)
_Dates_
- Notable topics, projects, or outcomes.

---

## Volunteer & Community (optional)

### Organization – Role
_Dates_
- What you did, who it helped, and any measurable outcomes.

---

## Projects (optional)

### Project Name – Short description
- What it does and why it matters; link to repo or demo if public.
- Technologies used; your role.

---

_Short closing line (optional): open to collaboration, roles, or inquiries._
