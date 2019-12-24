---
title: Deep learning for variant calling
summary: Generating pileup images from DNA sequencing data and using convolutional neural nets for variant calling.
date: "2018-08-27T00:00:00Z"

# Optional external URL for project (replaces project detail page).
# external_link: ""

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
# Focal points: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight.
image:
  caption: ""
  focal_point: ""
  preview_only: false

# links:    
# - icon: twitter
#   icon_pack: fab
#   name: Follow
#   url: https://twitter.com/georgecushen
# url_code: ""
# url_pdf: ""
# url_slides: ""
# url_video: ""

# Slides (optional).
#   Associate this project with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
# slides: example
---

Experimenting with new ways of generating pileup images from DNA sequencing data to increase variant calling accuracy. The machine learning pipeline involves parsing sequencing data files and creating pileup images, as well as training CNNs for classification (written with PyTorch and fastai).