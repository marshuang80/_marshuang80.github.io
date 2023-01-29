---
title: 'Self-supervised learning for medical image classification: a systematic review and implementation guidelines'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - Rui Yan
  - Liangqiong Qu
  - Qingyue Wei
  - admin
  - Liyue Shen
  - Daniel Rubin
  - Lei Xing
  - Yuyin Zhou

# Author notes (optional)
author_notes:

date: '2023-01-02T00:00:00Z'
doi: 'https://doi.org/10.1109/TMI.2022.3233574'

# Schedule page publish date (NOT publication's date).
publishDate: '2023-01-02T00:00:00Z'

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['2']

# Publication name and optional abbreviated publication name.
publication: In *IEEE Transactions on Medical Imaging*
publication_short: IEEE Transactions on Medical Imaging 

abstract: The collection and curation of large-scale medical datasets from multiple institutions is essential for training accurate deep learning models, but privacy concerns often hinder data sharing. Federated learning (FL) is a promising solution that enables privacy-preserving collaborative learning among different institutions, but it generally suffers from performance deterioration due to heterogeneous data distributions and a lack of quality labeled data. In this paper, we present a robust and label-efficient self-supervised FL framework for medical image analysis. Our method introduces a novel Transformer-based self-supervised pre-training paradigm that pre-trains models directly on decentralized target task datasets using masked image modeling, to facilitate more robust representation learning on heterogeneous data and effective knowledge transfer to downstream models. Extensive empirical results on simulated and real-world medical imaging non-IID federated datasets show that masked image modeling with Transformers significantly improves the robustness of models against various degrees of data heterogeneity. Notably, under severe data heterogeneity, our method, without relying on any additional pre-training data, achieves an improvement of 5.06%, 1.53% and 4.58% in test accuracy on retinal, dermatology and chest X-ray classification compared to the supervised baseline with ImageNet pre-training. In addition, we show that our federated self-supervised pre-training methods yield models that generalize better to out-of-distribution data and perform more effectively when fine-tuning with limited labeled data, compared to existing FL algorithms. 

# Summary. An optional shortened abstract.
summary:  In this paper, we present a robust and label-efficient self-supervised FL framework for medical image analysis. Our method introduces a novel Transformer-based self-supervised pre-training paradigm that pre-trains models directly on decentralized target task datasets using masked image modeling, to facilitate more robust representation learning on heterogeneous data and effective knowledge transfer to downstream models. 

tags: []

# Display this page in the Featured widget?
featured: false 

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org
url_pdf: 'https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=10004993'
url_code: 'https://github.com/rui-yan/SSL-FL'

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
projects:
  - []

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: ""
---
