---
title: "Design & Tech"
permalink: /design/
layout: single
author_profile: true
toc: true
toc_sticky: true
toc_label: "Projects"
excerpt: "Devices, installations and interactive design that make hidden risks and barriers visible."
detector_gallery:
  - url: /assets/images/portfolio/detector/detector-prototype.jpg
    image_path: /assets/images/portfolio/detector/detector-prototype-th.jpg
    alt: "Working prototype with dust sensor, traffic-light LED module and vibration motor wired to a microcontroller board"
    title: "Working prototype: dust sensor, LED alert lights and vibration motor"
  - url: /assets/images/portfolio/detector/detector-smoke-test.jpg
    image_path: /assets/images/portfolio/detector/detector-smoke-test-th.jpg
    alt: "Testing the prototype with incense smoke drifting over the sensor"
    title: "Testing the sensor’s response with incense smoke"
  - url: /assets/images/portfolio/detector/detector-board.jpg
    image_path: /assets/images/portfolio/detector/detector-board-th.jpg
    alt: "Close-up of the microcontroller board and wiring"
    title: "Wiring the microcontroller board"
---

These projects turn what I learned in research and fieldwork into things people can wear, touch and see.

<div class="project" markdown="1">

## Wearable Dust Detector & App

<p class="project__meta">Project initiator & developer · In progress</p>
<div class="tag-row"><span>Hardware</span><span>App development</span><span>Occupational health</span></div>

I am developing a wearable dust detector and companion app for stone-cutting workers. The device monitors PM2.5 and PM10 and gives light and sound alerts when dust levels are high, so that changes in exposure are easier to notice during work. The app tracks dust trends over time and shows device status and health guidance. The design grew out of my fieldwork on pneumoconiosis and my interest in making occupational exposure visible.

<figure><img src="{{ "/assets/images/portfolio/wearable-exploded.webp" | relative_url }}" alt="Exploded concept rendering of a wearable dust detector with a black enclosure and colour indicator lights" width="1024" height="1536" style="max-height:340px; width:auto; max-width:100%; margin:auto; display:block;" loading="lazy"><figcaption>Concept rendering of the detector’s internal assembly: enclosure, indicator lights, electronics, sensor, battery and vibration module.</figcaption></figure>

{% include gallery id="detector_gallery" layout="third" caption="Building and testing the prototype. Click a photo to enlarge it." %}

</div>

<div class="project" markdown="1">

## BREATH·LEDGER

<p class="project__meta">Interactive installation</p>
<div class="tag-row"><span>Interaction design</span><span>Installation</span></div>

**Mask Interaction Demo**

{% include video id="jrOOskPCdiQ" provider="youtube" %}

BREATH·LEDGER is an interactive installation inspired by my pneumoconiosis fieldwork in Pingxiang. A family photograph is obscured by a layer of digital dust. When a visitor approaches and puts on a mask, the dust clears; when the visitor leaves, it returns. The interaction makes a largely overlooked injury visible and invites reflection on the tension between earning a living and protecting one’s health, and on how the burden of care falls on individuals and families.

[Watch “Mask Interaction Demo” on YouTube](https://youtu.be/jrOOskPCdiQ){: .btn .btn--primary}

</div>

<div class="project" markdown="1">

## Invisible Barriers

<p class="project__meta">An interactive installation translating urban accessibility through touch and sound · January–September 2026</p>
<div class="tag-row"><span>Figma</span><span>Blender</span><span>Arduino</span><span>Accessibility</span></div>

This project asks why accessibility infrastructure so often fails on everyday streets, and how those failures affect the independent mobility of blind and visually impaired people. Through public interviews, case studies and spatial research, I found that broken, blocked or poorly maintained tactile paving is part of a wider urban system that treats sight as the default. In response, I translated common obstacles, tactile paving patterns and street furniture into a modular tactile language. Visitors explore the pieces by touch, and the system turns their movement into sound, so that barriers sighted people rarely notice become something to feel and hear.

<figure>
  <a href="{{ "/assets/images/portfolio/invisible-barriers/page-1.jpg" | relative_url }}"><img src="{{ "/assets/images/portfolio/invisible-barriers/page-1.jpg" | relative_url }}" alt="Invisible Barriers project board: title, introduction and news reports on blocked tactile paving" loading="lazy"></a>
  <figcaption>Introduction and inspiration: mobility barriers for visually impaired people.</figcaption>
</figure>
<figure>
  <a href="{{ "/assets/images/portfolio/invisible-barriers/page-2.jpg" | relative_url }}"><img src="{{ "/assets/images/portfolio/invisible-barriers/page-2.jpg" | relative_url }}" alt="Research board: public interviews, common obstacles on tactile paving and the consequences of invisible barriers" loading="lazy"></a>
  <figcaption>Research: public interviews and why the physical environment becomes harder for disabled people.</figcaption>
</figure>
<figure>
  <a href="{{ "/assets/images/portfolio/invisible-barriers/page-3.jpg" | relative_url }}"><img src="{{ "/assets/images/portfolio/invisible-barriers/page-3.jpg" | relative_url }}" alt="Ideation board: concept development, interactive logic, Arduino wiring and map design" loading="lazy"></a>
  <figcaption>Ideation, interactive logic, technical support and map design.</figcaption>
</figure>
<figure>
  <a href="{{ "/assets/images/portfolio/invisible-barriers/page-4.jpg" | relative_url }}"><img src="{{ "/assets/images/portfolio/invisible-barriers/page-4.jpg" | relative_url }}" alt="3D design board: modular tactile pieces, material experiments and sound research" loading="lazy"></a>
  <figcaption>3D design, module exploration, material experiments and sound research.</figcaption>
</figure>
<figure>
  <a href="{{ "/assets/images/portfolio/invisible-barriers/page-5.jpg" | relative_url }}"><img src="{{ "/assets/images/portfolio/invisible-barriers/page-5.jpg" | relative_url }}" alt="Final display of the white tactile installation, with visitor feedback and reflective conclusion" loading="lazy"></a>
  <figcaption>Final display, visitor feedback and reflective conclusion.</figcaption>
</figure>

</div>
