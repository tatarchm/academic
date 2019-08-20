---
title: "3D-Reconstruction of Indoor Environments from Human Activity"
authors:
- Barbara Frank
- Michael Ruhnke
- Maxim Tatarchenko
- Wolfram Burgard
date: "2015-05-01T00:00:00Z"
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
publication: In *IEEE International Conference on Robotics and Automation 2015*
publication_short: In *ICRA*

abstract: Observing human activities can reveal a lot about the structure of the environment, the objects contained therein and also their functionality. This knowledge, in turn, can be useful for robots interacting with humans or for robots performing mobile manipulation tasks. In this paper, we present an approach to infer the geometric and functional structure of the environment and the position of certain relevant objects in it from human activity. We observe this activity using a full-body motion capture system consisting of a set of inertial measurement units. This is a hard problem since our data suit provides odometry estimates only, which severely drift over time. Therefore, we regard the objects inferred from the activities as landmarks in a graph-based simultaneous localization and mapping problem, which we optimize to obtain accurate estimates about the poses of the objects and the trajectory of the human. In extensive experiments, we demonstrate the effectiveness of the proposed method for the reconstruction of 3D representations. The resulting models not only contain a geometric but also a functional description of the environment and naturally provide a segmentation into individual objects.

# Summary. An optional shortened abstract.
summary: ICRA 2015

tags: []
featured: true

links:
url_pdf: https://lmb.informatik.uni-freiburg.de/Publications/2015/Tat15/frank15icra.pdf
# url_code: 'https://github.com/lmb-freiburg/mv3d'
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
