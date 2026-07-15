---
permalink: /MadeByMiller/
title: "Made By Miller"
author_profile: true

projects:
  - image_path: /images/personal/cat.jpeg
    alt: "stained glass"
    title: ""
    excerpt: "Stained Glass Golfers (2026)"
  - image_path: /images/personal/lucas_eithin.jpeg
    alt: "cutting boards"
    title: ""
    excerpt: "Woven Cutting Boards (2026)"

  - image_path: /images/personal/lucas_full.jpeg
    alt: "stained glass"
    title: ""
    excerpt: "Stained Glass Figure Skaters (2026)"
  - image_path: /images/personal/cat.jpeg
    alt: "artfest"
    title: ""
    excerpt: "Cutting Boards (2026)"
  - image_path: /images/personal/lucas_eithin.jpeg
    alt: "mirror"
    title: ""
    excerpt: "Stained Glass Mirror (2026)"

  - image_path: /images/personal/lucas_full.jpeg
    alt: "stained glass"
    title: ""
    excerpt: "Stained Glass Aurora (2025)"
  - image_path: /images/personal/cat.jpeg
    alt: "stained glass"
    title: ""
    excerpt: "Stained Glass Mosaic (2025)"
  - image_path: /images/personal/lucas_eithin.jpeg
    alt: "cutting board"
    title: ""
    excerpt: "Chaos Cutting Board (2025)"

  - image_path: /images/personal/lucas_full.jpeg
    alt: "stained glass"
    title: ""
    excerpt: "Stained Glass Salamander (2025)"
  - image_path: /images/personal/cat.jpeg
    alt: "stained glass"
    title: ""
    excerpt: "Stained Glass Thistle (2025)"
  - image_path: /images/personal/lucas_eithin.jpeg
    alt: "cutting board"
    title: ""
    excerpt: "Weave Cutting Board (2024)"

  - image_path: /images/personal/lucas_full.jpeg
    alt: "mirror"
    title: ""
    excerpt: "Wooden Mirror V2 (2024)"
  - image_path: /images/personal/cat.jpeg
    alt: "stained glass"
    title: ""
    excerpt: "Stained Glass Dragon Flies (2024)"
  - image_path: /images/personal/lucas_eithin.jpeg
    alt: "refurbishment"
    title: ""
    excerpt: "Chair Refurbishment (2024)"

  - image_path: /images/personal/lucas_full.jpeg
    alt: "boxes"
    title: ""
    excerpt: "Tiny Boxes (2024)"
  - image_path: /images/personal/cat.jpeg
    alt: "mirror"
    title: ""
    excerpt: "Wooden Mirror (2023)"
  - image_path: /images/personal/lucas_eithin.jpeg
    alt: "sculpture"
    title: ""
    excerpt: "Fish (2023)"

  - image_path: /images/personal/lucas_full.jpeg
    alt: "restoration"
    title: ""
    excerpt: "Slot Machine Restoration (2023)"
  - image_path: /images/personal/cat.jpeg
    alt: "cutting board"
    title: ""
    excerpt: "Charcuterie Boards (2023)"
  - image_path: /images/personal/lucas_eithin.jpeg
    alt: "cutting baord"
    title: ""
    excerpt: "3D Cutting Board (2023)"

  - image_path: /images/personal/lucas_full.jpeg
    alt: "sculpture"
    title: ""
    excerpt: "Saw Tree Sculpture (2023)"
  - image_path: /images/personal/cat.jpeg
    alt: "refurbishment"
    title: ""
    excerpt: "Bench Refurbishment (2023)"
  - image_path: /images/personal/lucas_eithin.jpeg
    alt: "game board"
    title: ""
    excerpt: "Rummoli Game Board (2022)"

  - image_path: /images/personal/lucas_full.jpeg
    alt: "sign"
    title: ""
    excerpt: "Wooden Ski Sign (2022)"
  - image_path: /images/personal/cat.jpeg
    alt: "sculpture"
    title: ""
    excerpt: "Copper Wire Tree V2 (2022)"
  - image_path: /images/personal/lucas_eithin.jpeg
    alt: "oil painting"
    title: ""
    excerpt: "Oil Painting - Bella (2021)"

  - image_path: /images/personal/lucas_full.jpeg
    alt: "rings"
    title: ""
    excerpt: "Spoon Rings (2021)"
  - image_path: /images/personal/cat.jpeg
    alt: "propagation station"
    title: ""
    excerpt: "Plant Propagation Station (2021)"
  - image_path: /images/personal/lucas_eithin.jpeg
    alt: "upcycling"
    title: ""
    excerpt: "Upcycled Wooden Stool (2021)"

  - image_path: /images/personal/lucas_full.jpeg
    alt: "stained glass"
    title: ""
    excerpt: "Stained Glass Cardinal (2021)"
  - image_path: /images/personal/cat.jpeg
    alt: "recycled electronic sculpture"
    title: ""
    excerpt: "Tiny Painter V2 (2021)"
  - image_path: /images/personal/lucas_eithin.jpeg
    alt: "recycled electronic sculpture"
    title: ""
    excerpt: "Tiny Painter (2019)"

  - image_path: /images/personal/lucas_full.jpeg
    alt: "sculpture"
    title: ""
    excerpt: "Copper Wire Tree (2019)"
  - image_path: /images/personal/cat.jpeg
    alt: "mosaic"
    title: ""
    excerpt: "Stained Glass Mosaic (2018)"
  - image_path: /images/personal/lucas_eithin.jpeg
    alt: "lino block print"
    title: ""
    excerpt: "Maple Leaf Print (2017)"

---

These are all things that I have made over the past few years

<div class="madebymiller-grid">

{% for project in page.projects %}

<div class="project-card">

<img src="{{ project.image_path }}" alt="{{ project.alt }}">

<h3>{{ project.title }}</h3>

<p>{{ project.excerpt }}</p>

</div>

{% endfor %}

</div>