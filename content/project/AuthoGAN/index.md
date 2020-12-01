---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "AuthorGAN: Improving GAN Reproducibility using a Modular GAN Framework"
summary: "Toolkit for code-less authoring of GANs. Introducing a new abstractive view of the GAN framework which unifies various GANs. Unification allows users to commix different GAN components"
authors: []
tags: []
categories: []
date: 2019-11-06T20:33:18+05:30

# Optional external URL for project (replaces project detail page).
external_link: ""

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
# Focal points: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight.
image:
  caption: ""
  focal_point: ""
  preview_only: false

# Custom links (optional).
#   Uncomment and edit lines below to show custom links.
# links:
# - name: Follow
#   url: https://twitter.com
#   icon_pack: fab
#   icon: twitter

url_code: "https://github.com/IBM/gan-toolkit"
url_pdf: "https://arxiv.org/abs/1911.13250"
url_slides: ""
url_video: ""

# Slides (optional).
#   Associate this project with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
slides: ""
---
Generative models are becoming increasingly popular in the literature, with Gener- ative Adversarial Networks (GAN) being the most successful variant, yet. With this increasing demand and popularity, it is becoming equally difficult and challenging to implement and consume GAN models. A qualitative user survey conducted across 47 practitioners show that expert level skill is required to use GAN model for a given task, despite the presence of various open source libraries. In this research, we propose a novel system called AuthorGAN, aiming to achieve true democratization of GAN authoring. A highly modularized library agnostic repre- sentation of GAN model is defined to enable interoperability of GAN architecture across different libraries such as Keras, Tensorflow, and PyTorch. An intuitive drag-and-drop based visual designer is built using node-red platform to enable custom architecture designing without the need for writing any code. Five different GAN models are implemented as a part of this framework and the performance of the different GAN models are shown using the benchmark MNIST dataset.
