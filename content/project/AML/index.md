---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "Tranfering Adversarial Perturbation"
summary: ""
authors: []
tags: []
categories: []
date: 2019-05-06T20:04:15+05:30

# Optional external URL for project (replaces project detail page).
external_link: ""  

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
# Focal points: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight.
image:
  caption: ""
  focal_point: "smart"
  preview_only: false

# Custom links (optional).
#   Uncomment and edit lines below to show custom links.
# links:
# - name: Follow
#   url: https://twitter.com
#   icon_pack: fab
#   icon: twitter

url_code: ""
url_pdf: "https://drive.google.com/file/d/1x-lCISU9-7J7y7vtK4Iang3MNS2wseTK/view?usp=sharing"
url_slides: ""
url_video: ""

# Slides (optional).
#   Associate this project with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
slides: ""
---
Deep learning models have been shown to perform extremely well for many image based tasks. Such tasks include image classification, image generation, and image caption generation, etc. For such tasks deep learning methods have shown to understand the information present in images and make an intelligent decision.

A lot of what such models learn is dependent on the given data set. Is it actually possible to enhance information present in the data by adding perturbation and noise to the data? We are interested to find a possible answer for this question.

We propose an algorithm for transferring of data perturbation across different models and domains. We are interested in transferring adversarial data perturbations as attacks on the model
- Transfer learning to learn perturbations for a model. Adapting noise learned for one model, to another model.
- Maintaining the visual appearance of data samples after
transferring perturbations.
- Adapting noise with just one iteration of the dataset or 1-epoch (this reduces the computational complexity)