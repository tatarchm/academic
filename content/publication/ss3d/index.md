---
title: "Self-supervised 3D Shape and Viewpoint Estimation from Single Images for Robotics"
authors:
- Oier Mees
- Maxim Tatarchenko
- Thomas Brox
- Wolfram Burgard
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
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: In *IEEE/RSJ International Conference on Intelligent Robots and Systems 2019*
publication_short: In *IROS*

abstract: We present a convolutional neural network for joint 3D shape prediction and viewpoint estimation from a single input image. During training, our network gets the learning signal from a silhouette of an object in the input image - a form of self-supervision. It does not require ground truth data for 3D shapes and the viewpoints. Because it relies on such a weak form of supervision, our approach can easily be applied to real-world data. We demonstrate that our method produces reasonable qualitative and quantitative results on natural images for both shape estimation and viewpoint prediction. Unlike previous approaches, our method does not require multiple views of the same object instance in the dataset, which significantly expands the applicability in practical robotics scenarios. We showcase it by using the hallucinated shapes to improve the performance on the task of grasping real-world objects both in simulation and with a PR2 robot.

# Summary. An optional shortened abstract.
summary: IROS 2019

tags: []
featured: true

links:
url_pdf: https://lmb.informatik.uni-freiburg.de/Publications/2019/TB19a/ss3d_paper.pdf
# rl_code: 'https://github.com/lmb-freiburg/mv3d'
# url_dataset: ''
# url_poster: ''
# url_project: 'https://lmb.informatik.uni-freiburg.de/people/tatarchm/mv3d/'
# url_slides: ''
# url_source: ''
url_video: 'https://www.youtube.com/watch?v=oQgHG9JdMP4'

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
