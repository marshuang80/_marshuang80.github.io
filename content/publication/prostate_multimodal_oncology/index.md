---
title: 'Development and validation of a prognostic AI biomarker using multi-modal deep learning with digital histopathology in localized prostate cancer on NRG Oncology phase III clinical trials.'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - Andre Esteva
  - Jean Feng
  - admin
  - Douwe Van der Wal
  - Jeffry Simko
  - Sandy DeVries
  - Emmalyn Chen
  - Edward M Schaeffer
  - Todd Matthew Morgan
  - Jedidiah Mercer Monson
  - Farah Naz
  - James Wallace
  - Michelle J Ferguson
  - Jean-Paul Bahary
  - Howard M Sandler
  - Phuoc T Tran
  - Daniel Eidelberg Spratt
  - Stephanie L Pugh
  - Felix Y Feng
  - Osama Mohamad

# Author notes (optional)
author_notes:

date: '2022-02-20T00:00:00Z'
doi: 'https://doi.org/10.1200/JCO.2022.40.6_suppl.222'

# Schedule page publish date (NOT publication's date).
publishDate: '2022-02-20T00:00:00Z'

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['2']

# Publication name and optional abbreviated publication name.
publication: In *Journal of Clinical Oncology*
publication_short: Journal of Clinical Oncology 

abstract: Background - Prognostication in localized prostate cancer is reliant on non-specific tools, an issue that leads to the over- and under-treatment of patients. Various tissue-based molecular biomarkers have attempted to fill this unmet need, but most lack prospective randomized trial validation. Herein, we train and validate prognostic biomarkers in localized prostate cancer using five phase III randomized trials, by leveraging multi-modal deep learning on digital histopathology. Methods - Histopathology image data was generated from pre-treatment biopsy slides in five NRG Oncology phase III randomized radiotherapy prostate cancer trials (RTOG 9202, 9408, 9413, 9910, and 0126). The trials were randomly split into training (80%) and validation (20%) cohorts. A multi-modal artificial intelligence (MMAI) architecture was developed to take clinicopathologic and image-based (histopathology) data as input and predict binary outcomes. Using this architecture, various models were trained to predict relevant clinical endpoints - biochemical recurrence (BCR), distant metastasis (DM), prostate cancer-specific survival (PCaSS), and overall survival (OS). These models were then validated for measures of prognostic discrimination using the time-based area under the curve (AUC) method. Results - Clinicopathologic and histopathology image data was available for 5,654 of 7,957 eligible patients (71.1%), yielding 16.1 TB of data from 16,204 histopathology slides of pretreatment biopsy samples. After training the models, locking them, and evaluating them on the validation cohort, we found that the MMAI prognostic model had superior discrimination compared to the NCCN model (PSA, T-stage, and Gleason score) for 5-year DM (AUC of 0.84 vs 0.73), 5-year BCR (AUC of 0.69 vs 0.58), 10-year PCaSS (AUC of 0.79 vs 0.66), and 10-year OS (AUC of 0.65 vs 0.58). Within each of the individual trials in the validation cohort, the MMAI-model had superior performance compared to NCCN risk groups for all clinical endpoints. Conclusions - This represents the first ever development and validation of prognostic biomarkers in localized prostate cancer using multiple large phase III clinical trials. We have successfully validated that our MMAI-prognostic biomarkers are superior to standard clinical and pathologic variables in identifying future BCR, DM, PCaSS, and OS. This massively scalable technology is feasible and can help personalize the management of prostate cancer patients. 

# Summary. An optional shortened abstract.
summary: Prognostication in localized prostate cancer is reliant on non-specific tools, an issue that leads to the over- and under-treatment of patients. Various tissue-based molecular biomarkers have attempted to fill this unmet need, but most lack prospective randomized trial validation. Herein, we train and validate prognostic biomarkers in localized prostate cancer using five phase III randomized trials, by leveraging multi-modal deep learning on digital histopathology. 
tags: []

# Display this page in the Featured widget?
featured: false

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://ascopubs.org/doi/abs/10.1200/JCO.2022.40.6_suppl.222'

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
