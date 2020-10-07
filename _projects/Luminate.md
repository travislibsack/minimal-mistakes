---
title: "Luminate"
excerpt: "A modular room lighting solution controlled from a laptop"
layout: single
classes: wide
header:
  overlay_image: /assets/images/luminate/luminate_room-lighting.jpg
  show_overlay_excerpt: true
  teaser: assets/images/luminate/luminate_hub.jpg
sidebar:
  - title: "Role"
    image: /assets/images/luminate/luminate_hub_350x250.jpg
    image_alt: "logo"
    text: "Personal Project"
  - title: "Skills Used"
    text: "Focused on learning KiCad to be applicable in other situations."
gallery:
  - url: /assets/images/luminate/luminate_connector-boards.jpg
    image_path: assets/images/luminate/luminate_connector-boards.jpg
    alt: "Luminate Satellite units"
  - url: /assets/images/luminate/luminate_connect-board-to-leds.jpg
    image_path: assets/images/luminate/luminate_connect-board-to-leds.jpg
    alt: "Satellite to LED Strip"
  - url: /assets/images/luminate/luminate_final-setup.jpg
    image_path: assets/images/luminate/luminate_final-setup.jpg
    alt: "Luminate Final Setup"
order: 3
---

Luminate was a room lighting projcet I made in 2017 to learn how to design and assemble surface mount components using [KiCad](https://kicad-pcb.org/), an open-source PCB design software (alternative to Eagle CAD).

The final design consisted of a main contol unit with docking stations where different satellite strips are attached. Below is a gallery of the satellite units & final installation: 

{% include gallery caption="Gallery of Luminate Images" %}

The controls were done on a Rasbperry Pi (pictured above) and commands were delivered from scripts on my laptop to change brightness and color. 

#### Documents
+ [Quad Chart]({{site.baseurl}}/assets/pdfs/quadcharts/Luminate-Quad_Chart.pdf)<br>
