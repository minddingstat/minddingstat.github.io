---
layout: splash
permalink: /

header:
  image: /assets/img/main.png

feature_row1:
  - image_path: /assets/img/experiment.png
    alt: "placeholder image 5"
    title: "Clinical Trial"
    excerpt: 'Clinical Trial'
    url: "/categories/ClinicalTrial/"
    btn_label: "Read More"
    btn_class: "btn--primary"
  - image_path: /assets/img/bio.png
    alt: "placeholder image 4"
    title: "Survival Analysis"
    excerpt: 'Survival Analysis'
    url: "categories/SurvivalAnalysis/"
    btn_label: "Read More"
    btn_class: "btn--primary"
  - image_path: /assets/img/link.png
    alt: "placeholder image 3"
    title: "Glm"
    excerpt: 'Glm'
    url: "/categories/Glm/"
    btn_label: "Read More"
    btn_class: "btn--primary"
feature_row2:
  - image_path: /assets/img/bayes.png
    alt: "placeholder image 2"
    title: "Machine Learning"
    excerpt: 'Machine Learning'
    url: "categories/Bayesian/"
    btn_label: "Read More"
    btn_class: "btn--primary"
  - image_path: /assets/img/others.png
    alt: "placeholder image 6"
    title: "Others"
    excerpt: '해석학 등 기타 내용'
    url: "/categories/others/"
    btn_label: "Read More"
    btn_class: "btn--primary"
    
    

    
---

{% include feature_row id="intro" type="center"%}
{% include feature_row id="feature_row1" %}
{% include feature_row id="feature_row2" %}
