---
title: 'ConnectedUNets++: Mass Segmentation from Whole Mammographic Images'

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

date: '2022-08-23T00:00:00Z'
doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: '2022-08-23T00:00:00Z'

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['1']

# Publication name and optional abbreviated publication name.
publication: In *International Symposium on Visual Computing*
publication_short: In *ISVC*

abstract: "Deep learning has made a breakthrough in medical image segmentation in recent years due to its ability to extract high-level features without the need for prior knowledge. In this context, UNet is one of the most advanced medical image segmentation models, with promising results in mammography. Despite its excellent overall performance in segmenting multimodal medical images, the traditional U-Net structure appears to be inadequate in various ways. There are certain U-Net design modifications, such as MultiResUNet, Connected-UNets and AU-Net, that have improved overall performance in areas where the conventional U-Net architecture appears to be deficient. Following the success of UNet and its variants, we have presented two enhanced versions of the Connected-UNets architecture: ConnectedUNets+ and ConnectedUNets++. In ConnectedUNets+, we have replaced the simple skip connections of Connected-UNets architecture with residual skip connections, while in ConnectedUNets++, we have modified the encoder decoder structure along with employing residual skip connections. We have evaluated our proposed architectures on two publicly available datasets, the Curated Breast Imaging Subset of Digital Database for Screening Mammography (CBIS-DDSM) and INbreast."

# Summary. An optional shortened abstract.
summary: "There are certain U-Net design modifications, such as MultiResUNet, Connected-UNets and AU-Net, that have improved overall performance in areas where the conventional U-Net architecture appears to be deficient. Following the success of UNet and its variants, we have presented two enhanced versions of the Connected-UNets architecture: ConnectedUNets+ and ConnectedUNets++."

tags: ["Convolutional Neural Network, Mammogram, Semantic Segmentation, U-Net, ConnectedU-Nets, MultiResUNet"]

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: ''
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
  caption: 'ConnectedUNets++ Architecture'
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

# {{% callout note %}}
# Click the _Cite_ button above to demo the feature to enable visitors to import publication metadata into their reference management software.
# {{% /callout %}}

# {{% callout note %}}
# Create your slides in Markdown - click the _Slides_ button to check out the example.
# {{% /callout %}}

# Supplementary notes can be added here, including [code, math, and images](https://wowchemy.com/docs/writing-markdown-latex/).
