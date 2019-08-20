---
title: "Multi-view 3D Models from Single Images with a Convolutional Network"
authors:
- Maxim Tatarchenko
- Alexey Dosovitskiy
- Thomas Brox
date: "2013-07-01T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2017-01-01T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: In *European Conference on Computer Vision*
publication_short: In *ECCV*

abstract: We present a convolutional network capable of inferring a 3D representation of a previously unseen object given a single image of this object. Concretely, the network can predict an RGB image and a depth map of the object as seen from an arbitrary view. Several of these depth maps fused together give a full point cloud of the object. The point cloud can in turn be transformed into a surface mesh. The network is trained on renderings of synthetic 3D models of cars and chairs. It successfully deals with objects on cluttered background and generates reasonable predictions for real images of cars.

# Summary. An optional shortened abstract.
summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags:
- Source Themes
featured: true

links:
url_pdf: https://lmb.informatik.uni-freiburg.de/Publications/2016/TDB16a/paper-mv3d.pdf
url_code: 'https://github.com/lmb-freiburg/mv3d'
# url_dataset: ''
# url_poster: ''
url_project: 'https://lmb.informatik.uni-freiburg.de/people/tatarchm/mv3d/'
# url_slides: ''
# url_source: ''
# url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/pLCdAaMFLTE)'
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
