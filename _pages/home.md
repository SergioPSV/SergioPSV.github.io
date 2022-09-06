---
title: "RENALMRI.org"
layout: splash
permalink: /
date: 2020-04-09T12:00:00-04:00

header:
  overlay_color: "#000"
  overlay_filter: "0.1"
  overlay_image: /assets/images/header_parenchima.png

intro:
  - excerpt: 'Nullam suscipit et nam, tellus velit pellentesque at malesuada, enim eaque. Quis nulla, netus tempor in diam gravida tincidunt, *proin faucibus* voluptate felis id sollicitudin. Centered with `type="center"`'

feature_row:
  - image_path: assets/images/authors/alexandra-ljimani.jpeg
    image_caption: "[DR. ALEXANDRA LJIMANI](https://unsplash.com/)"
    alt: "DR. ALEXANDRA LJIMANI"
  - image_path: /assets/images/authors/anna-caroli.jpeg
    alt: "DR. ANNA CAROLI"
    image_caption: "[DR. ANNA CAROLI](https://unsplash.com/)"
  - image_path: assets/images/authors/pim-pullens.jpeg
    alt: "DR. IR. PIM PULLENS"
    image_caption: "[DR. IR. PIM PULLENS](https://unsplash.com/)"




feature_row2:
  - image_path: /assets/images/unsplash-gallery-image-2-th.jpg
    alt: "placeholder image 2"
    title: "Placeholder Image Left Aligned"
    excerpt: 'This is some sample content that goes here with **Markdown** formatting. Left aligned with `type="left"`'
    url: "#test-link"
    btn_label: "Read More"
    btn_class: "btn--primary"
feature_row3:
  - image_path: /assets/images/unsplash-gallery-image-2-th.jpg
    alt: "placeholder image 2"
    title: "Placeholder Image Right Aligned"
    excerpt: 'This is some sample content that goes here with **Markdown** formatting. Right aligned with `type="right"`'
    url: "#test-link"
    btn_label: "Read More"
    btn_class: "btn--primary"
feature_row4:
  - title: "Participants"
    url: /participants/
    btn_label: "Show"
    btn_class: "btn--primary"
---

{% capture notice-text %}
Twitter handle: @renalMRI

Check out our [renal MRI resources](https://renalmri.org/news)


**Coordinating research on renal MRI biomarkers for clinical practice, drug development and basic research.**
The rising prevalence of Chronic Kidney Disease (CKD) poses a major public health challenge affecting >10% of the population. There exists an urgent need for better biomarkers to identify patients that are at risk of progression, or are likely to respond to (candidate) therapeutics. Magnetic Resonance Imaging (MRI) biomarkers can help to fill this gap, as they are uniquely able to track disease progression and treatment effects in the tissue itself and in a non-invasive manner (see here for a position statement by leading scientists and clinicians).
{% endcapture %}

<div class="notice--info" align="justify">
  <h1 align="center">MAGNETIC RESONANCE IMAGING
BIOMARKERS FOR KIDNEY DISEASE</h1>
  {{ notice-text | markdownify }}
</div>

{% capture mrs-workshop-text %}
In recent years, the clinical interest in renal MRI has accelerated research and development and led to a growing excitement within an emerging multidisciplinary community of nephrologists, radiologists, surgeons, radiographers, physicists, computer scientists, pathologists and physiologists. Bi-annual international meetings have been held since 2015, and national and international consortia have been funded to work on standardization of methods, preclinical research and multi-centre clinical trials. The field has seen an increasing participation from charities and the private sector, including SME's, pharmaceutical industry and MRI scanner manufacturers.

**RENALMRI.org provides a central point of access to the renal MRI community and joins up all stakeholders with an aim to speed up translation into clinical practice, drug development and basic research. Check out our resources [here](https://renalmri.org/news)!**
{% endcapture %}


<div class="notice--success" align="justify">
  <h1 align="center">MISSION</h1>
  {{ mrs-workshop-text | markdownify }}
</div>

{% capture mrs-workshop-text %}
RENALMRI.org was created by the ongoing COST Action PARENCHIMA (CA16103) and will continue to be maintained by PARENCHIMA at until the end of the action (1 October 2021). Current planning foresees a handover of RENALMRI.org to a more informal networking of groups with an interest in MRI. A governance approach will be discussed and decided during the final PARENCHIMA meeting on the ISMRM-PARENCHIMA kidney MRI workshop in september 2021, and will be encoded in a dedicated governance section on this website.
{% endcapture %}


<div class="notice--success" align="justify">
  <h1 align="center">GOVERNANCE</h1>
  {{ mrs-workshop-text | markdownify }}
</div>

{% capture notice-text %}
The core team succeeds the PARENCHIMA Core Team, which consisted of

- Steven Sourbron (Chair)

- Christoffer Laustsen

- Frank Zöllner

- Thoralf Niendorf

- Anna Caroli

- Marcos Wolf
{% endcapture %}

<div class="notice--info" align="justify">
  <h1 align="center">RENALMRI.ORG CORE TEAM</h1>
  {{ notice-text | markdownify }}
</div>

{% include feature_row %}

{% include feature_row id="feature_row4" type="center" %}
<!-- {% include feature_row id="intro" type="center" %} -->
