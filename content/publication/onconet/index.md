---
title: 'OncoNet: Weakly Supervised Siamese Network to automate cancer treatment response assessment between longitudinal FDG PET/CT examinations'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - Anirudh Joshi
  - Sabri Eyuboglu
  - admin
  - Jared Dunnmon
  - Arjun Soin
  - Guido Davidzon
  - Akshay Chaudhari
  - Matthew P Lungren

# Author notes (optional)
author_notes:
  - 'Equal contribution'
  - 'Equal contribution'
  - 'Equal contribution'

date: '2020-04-24T00:00:00Z'
doi: 'https://doi.org/10.48550/arXiv.2108.02016'

# Schedule page publish date (NOT publication's date).
publishDate: '2020-04-24T00:00:00Z'

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['3']

# Publication name and optional abbreviated publication name.
publication: arXiv
publication_short: arXiv

abstract: FDG PET/CT imaging is a resource intensive examination critical for managing malignant disease and is particularly important for longitudinal assessment during therapy. Approaches to automate longtudinal analysis present many challenges including lack of available longitudinal datasets, managing complex large multimodal imaging examinations, and need for detailed annotations for traditional supervised machine learning. In this work we develop OncoNet, novel machine learning algorithm that assesses treatment response from a 1,954 pairs of sequential FDG PET/CT exams through weak supervision using the standard uptake values (SUVmax) in associated radiology reports. OncoNet demonstrates an AUROC of 0.86 and 0.84 on internal and external institution test sets respectively for determination of change between scans while also showing strong agreement to clinical scoring systems with a kappa score of 0.8. We also curated a dataset of 1,954 paired FDG PET/CT exams designed for response assessment for the broader machine learning in healthcare research community. Automated assessment of radiographic response from FDG PET/CT with OncoNet could provide clinicians with a valuable tool to rapidly and consistently interpret change over time in longitudinal multi-modal imaging exams.

# Summary. An optional shortened abstract.
summary: In this work we develop onconet, novel machine learning algorithm that assesses treatment response from a 1,954 pairs of sequential fdg pet/ct exams through weak supervision using the standard uptake values (suvmax) in associated radiology reports. onconet demonstrates an auroc of 0.86 and 0.84 on internal and external institution test sets respectively for determination of change between scans while also showing strong agreement to clinical scoring systems with a kappa score of 0.8.
tags: ['Medical Images']

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://arxiv.org/abs/2108.02016'

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