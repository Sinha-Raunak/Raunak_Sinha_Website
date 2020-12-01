---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "Multi-label Triplet Embeddings for Image Annotation from User-Generated Tags"
summary: ""
authors: []
tags: []
categories: []
date: 2019-04-11T00:29:30+05:30

# Optional external URL for project (replaces project detail page).
external_link: ""

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
# Focal points: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight.
image:
  caption: "(Above) Labels for images samples. Labels include example of semantically simple and complex labels.

  (Below) Proposed architecture for choosing combination of various possible triplet loss"
  focal_point: ""
  preview_only: false

# Custom links (optional).
#   Uncomment and edit lines below to show custom links.
# links:
# - name: Follow
#   url: https://twitter.com
#   icon_pack: fab
#   icon: twitter

url_code: ""
url_pdf: "https://drive.google.com/file/d/1xQbKqXwsdOvf0cSTFoxOVRhaXYRdB7np/view?usp=sharing"
url_slides: ""
url_video: ""

# Slides (optional).
#   Associate this project with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
slides: ""
---
To predict (extract) semantic labels for a given image. This is achieved by using triplet loss on latent embedding (features) for images and text-labels.