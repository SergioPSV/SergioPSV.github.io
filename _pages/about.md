---
forms:
  - to: serhiy.parkhom@gmail.com
    subject: New submission!
    redirect: /
    form_engine: formspree
    placeholders: false
    fields: 
      - name: name
        input_type: text
        placeholder: Name
        required: true
      - name: email
        input_type: email
        placeholder: Email address
        required: true
      - name: sex
        input_type: radio
        placeholder: male
        required: true
      - name: sex
        input_type: radio
        placeholder: female
        required: true
      - name: message
        input_type: textarea
        placeholder: Message
        required: false
      - name: terms
        input_type: checkbox
        placeholder: I accept the terms and conditions
        required: true
      - name: submit
        input_type: submit
        placeholder: Submit form
        required: true
title: "About"
permalink: /about/
date: 2022-11-10T18:39:14+00:00
author_profile: false
---

RENALMRI.org is an open and growing network of researchers and clinicians bringing together, among others, nephrology, radiology, pathology, physiology and physics to promote the clinical translation of functional renal magnetic resonance imaging. If you want to join our efforts, please go to [https://renalmri.org/login](https://renalmri.org/login) to register with our services. If you have any issues, please contact the lead of working group 5.

See also our dissemination activities.

Follow us on Twitter ***@renalMRI***

Follow us on [ResearchGate](https://www.researchgate.net/project/PARENCHIMA-Magnetic-Resonance-Imaging-Biomarkers-for-Chronic-Kidney-Disease)

### PRIVACY NOTICE
This is the current version of our renal MRI privacy notice. For further questions please contact us on privacy@renalmri.org.

### PROJECT INFORMATION
RENALMRI.org is maintained by the COST Action PARENCHIMA (CA16103), supported by the European Cooperation in Science and Technology (COST).  

COST (www.cost.eu) is a funding organization for research and innovation networks.  Our Actions help connect research initiatives across Europe and beyond and enable researchers and innovators to grow their ideas in any science and technology field by sharing them with their peers. COST Actions are bottom-up networks with a duration of four years that boost research, innovation and careers.

{% if page.forms[0] %}{% include form.html form="1" %}{% endif %}
