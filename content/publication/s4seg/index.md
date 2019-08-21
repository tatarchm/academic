---
title: "Semi-Supervised Semantic Segmentation with High- and Low-level Consistency"
authors:
- Sudhanshu Mittal
- Maxim Tatarchenko
- Thomas Brox
date: "2019-08-01T00:00:00Z"
share: false  # Show social sharing links?
profile: false  # Show author profile?
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: ""

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["3"]

# Publication name and optional abbreviated publication name.
publication: In *arXiv (1908.05724)*
publication_short: In *arXiv*

abstract: The ability to understand visual information from limited labeled data is an important aspect of machine learning. While image-level classification has been extensively studied in a semi-supervised setting, dense pixel-level classification with limited data has only drawn attention recently. In this work, we propose an approach for semi-supervised semantic segmentation that learns from limited pixel-wise annotated samples while exploiting additional annotation-free images. It uses two network branches that link semi-supervised classification with semi-supervised segmentation including self-training. The dual-branch approach reduces both the low-level and the high-level artifacts typical when training with few labels. The approach attains significant improvement over existing methods, especially when trained with very few labeled samples. On several standard benchmarks - PASCAL VOC 2012, PASCAL-Context, and Cityscapes - the approach achieves new state-of-the-art in semi-supervised learning.

# Summary. An optional shortened abstract.
summary: arXiv 2019

tags: []
featured: true

links:
url_pdf: https://arxiv.org/pdf/1908.05724.pdf
url_code: 'https://github.com/sud0301/semisup-semseg'
# url_dataset: ''
# url_poster: ''
# url_project: 'https://lmb.informatik.uni-freiburg.de/people/tatarchm/mv3d/'
# url_slides: ''
# url_source: ''
# url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  caption: ''
  focal_point: ""
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
