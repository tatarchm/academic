---
title: "Octree Generating Networks: Efficient Convolutional Architectures for High-resolution 3D Outputs"
authors:
- Maxim Tatarchenko
- Alexey Dosovitskiy
- Thomas Brox
date: "2017-10-01T00:00:00Z"
share: false  # Show social sharing links?
profile: false  # Show author profile?
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: ""

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: In *International Conference on Computer Vision 2016*
publication_short: In *ICCV*

abstract: We present a deep convolutional decoder architecture that can generate volumetric 3D outputs in a compute- and memory-efficient manner by using an octree representation. The network learns to predict both the structure of the octree, and the occupancy values of individual cells. This makes it a particularly valuable technique for generating 3D shapes. In contrast to standard decoders acting on regular voxel grids, the architecture does not have cubic complexity. This allows representing much higher resolution outputs with a limited memory budget. We demonstrate this in several application domains, including 3D convolutional autoencoders, generation of objects and whole scenes from high-level representations, and shape from a single image.

# Summary. An optional shortened abstract.
summary: ICCV 2017

tags: []
featured: true

links:
url_pdf: 'https://lmb.informatik.uni-freiburg.de/Publications/2017/TDB17b/paper-ogn.pdf'
url_code: 'https://github.com/lmb-freiburg/ogn'
# url_dataset: ''
# url_poster: ''
url_project: 'https://lmb.informatik.uni-freiburg.de/people/tatarchm/ogn/'
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
