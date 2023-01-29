---
title: 'Multimodal fusion with deep neural networks for leveraging CT imaging and electronic health record: a case-study in pulmonary embolism detection'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - admin
  - Anuj Pareek
  - Roham Zamanian
  - Imon Banerjee
  - Matthew P. Lungren 

# Author notes (optional)
author_notes:

date: '2020-12-17T00:00:00Z'
doi: 'https://doi.org/10.1038/s41598-020-78888-w'

# Schedule page publish date (NOT publication's date).
publishDate: '2020-12-17T00:00:00Z'

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['2']

# Publication name and optional abbreviated publication name.
publication: In *Nature Scientific Reports*
publication_short: Nature Scientific Reports

abstract: Recent advancements in deep learning have led to a resurgence of medical imaging and Electronic Medical Record (EMR) models for a variety of applications, including clinical decision support, automated workflow triage, clinical prediction and more. However, very few models have been developed to integrate both clinical and imaging data, despite that in routine practice clinicians rely on EMR to provide context in medical imaging interpretation. In this study, we developed and compared different multimodal fusion model architectures that are capable of utilizing both pixel data from volumetric Computed Tomography Pulmonary Angiography scans and clinical patient data from the EMR to automatically classify Pulmonary Embolism (PE) cases. The best performing multimodality model is a late fusion model that achieves an AUROC of 0.947 [95% CI 0.946–0.948] on the entire held‑out test set, outperforming imaging‑only and EMR‑only single modality models.

# Summary. An optional shortened abstract.
summary: In this study, we developed and compared different multimodal fusion model architectures that are capable of utilizing both pixel data from volumetric Computed Tomography Pulmonary Angiography scans and clinical patient data from the EMR to automatically classify Pulmonary Embolism (PE) cases.
tags: []

# Display this page in the Featured widget?
featured: false

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://www.nature.com/articles/s41598-020-78888-w'

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
image:
  caption: ''
  focal_point: ''
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects: []

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: ""
---
