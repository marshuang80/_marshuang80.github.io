---
title: 'PENet—a scalable deep-learning model for automated diagnosis of pulmonary embolism using volumetric CT imaging'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - admin
  - Tanay Kothari
  - Imon Banerjee
  - Chris Chute
  - Robyn L Ball
  - Norah Borus
  - Andrew Huang
  - Bhavik N Patel
  - Pranav Rajpurkar
  - Jeremy Irvin
  - Jared Dunnmon
  - Joseph Bledsoe
  - Katie Shpanskaya
  - Abhay Dhaliwal
  - Roham Zamanian
  - Andrew Y Ng
  - Matthew P Lungren

# Author notes (optional)
author_notes:
  - 'Equal contribution'
  - 'Equal contribution'

date: '2020-04-24T00:00:00Z'
doi: 'https://doi.org/10.1038/s41746-020-00310-6'

# Schedule page publish date (NOT publication's date).
publishDate: '2020-04-24T00:00:00Z'

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['2']

# Publication name and optional abbreviated publication name.
publication: In *Nature Digital Medicine*
publication_short: Nature Digital Medicine

abstract: Pulmonary embolism (PE) is a life-threatening clinical problem and computed tomography pulmonary angiography (CTPA) is the gold standard for diagnosis. Prompt diagnosis and immediate treatment are critical to avoid high morbidity and mortality rates, yet PE remains among the diagnoses most frequently missed or delayed. In this study, we developed a deep learning model—PENet, to automatically detect PE on volumetric CTPA scans as an end-to-end solution for this purpose. The PENet is a 77-layer 3D convolutional neural network (CNN) pretrained on the Kinetics-600 dataset and fine-tuned on a retrospective CTPA dataset collected from a single academic institution. The PENet model performance was evaluated in detecting PE on data from two different institutions - one as a hold-out dataset from the same institution as the training data and a second collected from an external institution to evaluate model generalizability to an unrelated population dataset. PENet achieved an AUROC of 0.84 [0.82–0.87] on detecting PE on the hold out internal test set and 0.85 [0.81–0.88] on external dataset. PENet also outperformed current state-of-the-art 3D CNN models. The results represent successful application of an end-to-end 3D CNN model for the complex task of PE diagnosis without requiring computationally intensive and time consuming preprocessing and demonstrates sustained performance on data from an external institution. Our model could be applied as a triage tool to automatically identify clinically important PEs allowing for prioritization for diagnostic radiology interpretation and improved care pathways via more efficient diagnosis.

# Summary. An optional shortened abstract.
summary: The PENet is a 77-layer 3D convolutional neural network (CNN) pretrained on the Kinetics-600 dataset and fine-tuned on a retrospective CTPA dataset collected from a single academic institution. The PENet model performance was evaluated in detecting PE on data from two different institutions - one as a hold-out dataset from the same institution as the training data and a second collected from an external institution to evaluate model generalizability to an unrelated population dataset. ure published between 2012 and 2020. By means of this systematic review, we present current knowledge, summarize important results and provide implementation guidelines to serve as a reference for researchers interested in the application of multimodal fusion in medical imaging.
tags: []

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://www.nature.com/articles/s41746-020-0266-y'

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