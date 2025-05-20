---
layout: post
title: Acee's Photography
date: 2025-04-22 20:00:00
description: I use CanonM50m2 and SonyA7CR to capture architecture, intimate_landscape, landscape, portrait and street
tags: photography
categories: sample-posts
thumbnail: assets/img/intimate_landscape/Filoli1_SonyA7CR.jpg
images:
  lightbox2: true
  photoswipe: true
  spotlight: true
  venobox: true

gallery_architecture:
  - DC1_CanonM50m2.jpg
  - DC2_CanonM50m2.jpg
  - Fallingwater1_CanonM50m2.jpg
  - Fallingwater2_CanonM50m2.jpg
  - Filoli_SonyA7CR.jpg
  - SatherTower_CanonM50m2.jpg

gallery_intimate_landscape:
  - EdRLevinCountyPark_SonyA7CR_2025May4.jpg
  - Filoli1_SonyA7CR.jpg
  - Filoli2_SonyA7CR.jpg
  - GreatSmokyMountains1_CanonM50m2.jpg
  - GreatSmokyMountains2_CanonM50m2.jpg
  - GreatSmokyMountains3_CanonM50m2.jpg
  - LakeErie_CanonM50m2.jpg
  - Miami_CanonM50m2.jpg
  - Pittsburgh1_CanonM50m2_2025May10.jpg
  - Pittsburgh2_CanonM50m2_2025May12.jpg
  - Salt-Pond_Sunnyvale_SonyA7CR.jpg
  - SanFrancisco_CanonM50m2.jpg
  - Yosemite1_CanonM50m2.jpg
  - Yosemite2_CanonM50m2.jpg
  - Yosemite3_CanonM50m2.jpg

gallery_landscape:
  - DelValle_CanonM50m2.jpg
  - EdRLevinCountyPark1_SonyA7CR_2025May4.jpg
  - EdRLevinCountyPark2_SonyA7CR_2025May4.jpg
  - NiagaraFalls1_CanonM50m2.jpg
  - NiagaraFalls2_CanonM50m2.jpg
  - PuertoRico_Iphone12.jpg
  - SanFrancisco_CanonM50m2.jpg
  - Yosemite1_CanonM50m2.jpg
  - Yosemite2_CanonM50m2.jpg
  - Yosemite3_CanonM50m2.jpg
  - Yosemite4_CanonM50m2.jpg

gallery_portrait:
  - EdRLevinCountyPark_FujiX100V_2025May4.jpg
  - Filoli_SonyA7CR.jpg
  - Pittsburgh_CanonM50m2.jpg
  - Yosemite_CanonM50m2.jpg

gallery_street:
  - Filoli1_SonyA7CR.jpg
  - Filoli2_SonyA7CR.jpg
  - Pittsburgh1_CanonM50m2_2025May12.jpg
  - Pittsburgh2_CanonM50m2_2025May12.jpg
  - Pittsburgh3_CanonM50m2_2025May12.jpg
  - Pittsburgh4_CanonM50m2_2025May12.jpg
  - Pittsburgh5_CanonM50m2_2025May12.jpg
  - Pittsburgh6_CanonM50m2_2025May12.jpg
  - Pittsburgh7_CanonM50m2_2025May12.jpg
  - Pittsburgh8_CanonM50m2_2025May12.jpg

gallery_macro:
  - CarnegieMuseumOfArt1_CanonM502_2025May10.jpg
  - CarnegieMuseumOfArt2_CanonM502_2025May10.jpg
  - CarnegieMuseumOfArt3_CanonM502_2025May10.jpg
  - Filoli_SonyA7CR.jpg
  - Pittsburgh1_CanonM50m2_2025May10.jpg
  - Pittsburgh2_CanonM50m2_2025May12.jpg
  - Pittsburgh3_CanonM50m2_2025May12.jpg

gallery_museum:
  - CarnegieMuseumOfArt1_CanonM502_2025May10.jpg
  - CarnegieMuseumOfArt2_CanonM502_2025May10.jpg
  - CarnegieMuseumOfArt3_CanonM502_2025May10.jpg
  - CarnegieMuseumOfArt4_CanonM502_2025May10.jpg
  - CarnegieMuseumOfArt5_CanonM502_2025May10.jpg
  - CarnegieMuseumOfArt6_CanonM502_2025May10.jpg
  - CarnegieMuseumOfArt7_CanonM502_2025May10.jpg
  - CarnegieMuseumOfArt8_CanonM502_2025May10.jpg
---

The images in this post are all zoomable, arranged into different mini-galleries using different libraries.

## Architecture

{% for img in page.gallery_architecture %}

<div style="display: inline-block; text-align: center; margin: 10px;">
  <a href="/assets/img/acee_architecture/{{ img }}" data-lightbox="roadtrip" title="{{ img | split: '.' | first }}">
    <img src="/assets/img/acee_architecture/{{ img }}" style="width: 200px; height: auto;" />
  </a>
  <div style="font-size: 14px;">{{ img | split: '.' | first }}</div>
</div>
{% endfor %}

---

## Intimate Landscape

{% for img in page.gallery_intimate_landscape %}

<div style="display: inline-block; text-align: center; margin: 10px;">
  <a href="/assets/img/acee_intimate_landscape/{{ img }}" data-lightbox="roadtrip" title="{{ img | split: '.' | first }}">
    <img src="/assets/img/acee_intimate_landscape/{{ img }}" style="width: 200px; height: auto;" />
  </a>
  <div style="font-size: 14px;">{{ img | split: '.' | first }}</div>
</div>
{% endfor %}

---

## Landscape

{% for img in page.gallery_landscape %}

<div style="display: inline-block; text-align: center; margin: 10px;">
  <a href="/assets/img/acee_landscape/{{ img }}" data-lightbox="roadtrip" title="{{ img | split: '.' | first }}">
    <img src="/assets/img/acee_landscape/{{ img }}" style="width: 200px; height: auto;" />
  </a>
  <div style="font-size: 14px;">{{ img | split: '.' | first }}</div>
</div>
{% endfor %}

---

## Portrait

{% for img in page.gallery_portrait %}

<div style="display: inline-block; text-align: center; margin: 10px;">
  <a href="/assets/img/acee_portrait/{{ img }}" data-lightbox="roadtrip" title="{{ img | split: '.' | first }}">
    <img src="/assets/img/acee_portrait/{{ img }}" style="width: 200px; height: auto;" />
  </a>
  <div style="font-size: 14px;">{{ img | split: '.' | first }}</div>
</div>
{% endfor %}

---

## Street

{% for img in page.gallery_street %}

<div style="display: inline-block; text-align: center; margin: 10px;">
  <a href="/assets/img/acee_street/{{ img }}" data-lightbox="roadtrip" title="{{ img | split: '.' | first }}">
    <img src="/assets/img/acee_street/{{ img }}" style="width: 200px; height: auto;" />
  </a>
  <div style="font-size: 14px;">{{ img | split: '.' | first }}</div>
</div>
{% endfor %}

---

## Macro

{% for img in page.gallery_macro %}

<div style="display: inline-block; text-align: center; margin: 10px;">
  <a href="/assets/img/acee_macro/{{ img }}" data-lightbox="roadtrip" title="{{ img | split: '.' | first }}">
    <img src="/assets/img/acee_macro/{{ img }}" style="width: 200px; height: auto;" />
  </a>
  <div style="font-size: 14px;">{{ img | split: '.' | first }}</div>
</div>
{% endfor %}

---

## Museum

{% for img in page.gallery_museum %}

<div style="display: inline-block; text-align: center; margin: 10px;">
  <a href="/assets/img/acee_museum/{{ img }}" data-lightbox="roadtrip" title="{{ img | split: '.' | first }}">
    <img src="/assets/img/acee_museum/{{ img }}" style="width: 200px; height: auto;" />
  </a>
  <div style="font-size: 14px;">{{ img | split: '.' | first }}</div>
</div>
{% endfor %}
