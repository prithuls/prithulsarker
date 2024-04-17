---
title: 'MV-Swin-T: Mammogram Classification with Multi-view Swin Transformer'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - admin
  - Sushmita Sarker
  - George Bebis 
  - Alireza Tavakkoli


# Author notes (optional)
author_notes:
  - 'Equal contribution'
  - 'Equal contribution'

date: '2024-03-01T00:00:00Z'
doi: 'https://arxiv.org/abs/2402.16298'

# Schedule page publish date (NOT publication's date).
publishDate: '2024-01-02T00:00:00Z'

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['2']

# Publication name and optional abbreviated publication name.
publication: In *IEEE International Symposium on Biomedical Imaging*
publication_short: In *IEEE International Symposium on Biomedical Imaging*

abstract: Traditional deep learning approaches for breast cancer classification has predominantly concentrated on single-view analysis. In clinical practice, however, radiologists concurrently examine all views within a mammography exam, leveraging the inherent correlations in these views to effectively detect tumors. Acknowledging the significance of multi-view analysis, some studies have introduced methods that independently process mammogram views, either through distinct convolutional branches or simple fusion strategies, inadvertently leading to a loss of crucial inter-view correlations. In this paper, we propose an innovative multi-view network exclusively based on transformers to address challenges in mammographic image classification. Our approach introduces a novel shifted window-based dynamic attention block, facilitating the effective integration of multi-view information and promoting the coherent transfer of this information between views at the spatial feature map level. Furthermore, we conduct a comprehensive comparative analysis of the performance and effectiveness of transformer-based models under diverse settings, employing the CBIS-DDSM and Vin-Dr Mammo datasets. Our code is publicly available [here](https://github.com/prithuls/MV-Swin-T).

# Summary. An optional shortened abstract.
summary: Multi-view swin tran

tags: ["computer vision", "deep learning", "ai in healthcare", "transformer", "multi-view mammogram"]

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://arxiv.org/pdf/2402.16298.pdf'
url_code: ''
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''

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

