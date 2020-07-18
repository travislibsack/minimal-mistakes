---
title: "BaxterOSV"
excerpt: "An inexpensive, robust, and simple to use ventilator for developing countries during Spring 2020 COVID-19 outbreak"
layout: single
classes: wide
header:
  overlay_image: /assets/images/baxterosv/vent-v2-onpatient.png
  show_overlay_excerpt: true
  actions:
    - label: "Final Report"
      url: "/assets/pdfs/BaxterOSV_Final-Report.pdf"
  teaser: assets/images/baxterosv/vent-v2-onpatient.png
sidebar:
  - title: "Role"
    image: /assets/images/aquadio/Aquadio_350x250.png
    image_alt: "logo"
    text: "Electronics Designer, Protype Builder"
  - title: "Responsibilities"
    text: "Design of Wiring Harness/PCB and Sensor Firmware, Prototype Assembler & Debugger"
gallery:
  - url: /assets/images/baxterosv/vent-v1.png
    image_path: assets/images/baxterosv/vent-v1.png
    alt: "Ventilator, v1"
  - url: /assets/images/baxterosv/vent-v2.png
    image_path: assets/images/baxterosv/vent-v2.png
    alt: "Ventilator, v2"
  - url: /assets/images/baxterosv/vent-v3.png
    image_path: assets/images/baxterosv/vent-v3.png
    alt: "Ventilator, v3"
---

The COVID-19 crisis in 2020 posed an extreme threat to under-developed countries. Wite their lack of medical equipment and infrastructure needed for ventilators, they were going to be stuck without the equipment needed to effectively fight the dieases. The Baxter Open Source Ventilator (BaxterOSV) was designed to work in under-developed countries with limited access to medical supply chains. The design utilizes **off-the-shelf components** and a design that **creates its own pressure** to ventilate patients, not needing expensive hospital infrastructure.

This design participated in the [CoVent-19 Challange](https://www.coventchallenge.com/) run my Massachusetts General Hospital in Spring 2020 and made it as one of the **7 finalists** to the final round of the competition!

{% include gallery caption="Evolution of Ventilator Design" %}

BaxterOSV performed more consistently each breath when compared to industry products. A ventilator technician we partnerd with to test our system said:

> “Consistently we were able to safely administer ventilations to the patient, we were able to change the settings to accommodate any reasonable parameters, and do so safely, quickly, easily, and achieve results that were... surprisingly similar to our full anesthesia machine"

The validation for our system was done measuring the output with external sensors and comparing aginst our settings. Below is an example of a breath our ventilator was able to produce:

![Breath Profile]({{site.baseurl}}/assets/images/baxterosv/breath_graphs.png "Pressure, Volume, and Flow from our ventilator")

**Team:** *Jonathan Amory, Emmalyn Armstrong, Ben Bernard, Josef Biberstein, Casey Burhoe, Rawen Connor-McCoy, Norris Dale, Zackary DiCelico, Olivia Fowler, Gordon.Fream, James Heffernan, Travis Libsack, Emily Mickool, Nick Nelsonwood, Amanda Palma, Mae Pryor-Rosenstein, Sylvie Pryor-Rosensein, Toby Roy, Caden Theriault, Bodhi Wilkins, Alexander Willette, Jack Yebba*

#### Documents
+ [Quad Chart]({{site.baseurl}}/assets/pdfs/quadcharts/BaxterOSV-Quad_Chart.pdf)<br>
+ [Final Report]({{site.baseurl}}/assets/pdfs/BaxterOSV_Final-Report.pdf)<br>
+ [Video Example]({{site.baseurl}}/assets/images/baxterosv/May23-Prototype.MOV) 