---
title: EEG-based neurofeedback system
summary: Building an EEG-based brain-machine interface system as a prototype device for pain treatment.
# tags:
# - Deep Learning
date: "2019-01-27T00:00:00Z"

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

EEG-based neurofeedback system is based on trial pain level classification in real-time. This requires minimal intervention in feature selection for classifier training, and automatic rejection of noisy trials. Building a pipeline that streams raw EEG data from OpenVibe and outputing pain level classification labels is the basis of this project.