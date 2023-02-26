---
title: COVID 19 AI Diagnosis
summary: A Convolutional Neural Network which is trained to detect COVID 19 even in asymptotic patients using only cough recordings.
tags:
  - Deep Learning
# date: '2016-04-27T00:00:00Z'

# Optional external URL for project (replaces project detail page).
external_link: ''

image:
  caption: 
  focal_point: Smart

links:
  # - icon: twitter
  #   icon_pack: fab
  #   name: Follow
  #   url: https://twitter.com/georgecushen
url_code: 'https://github.com/dhivyasreedhar/Covid19CoughDetection'
url_pdf: ''
url_slides: ''
url_video: ''

# Slides (optional).
#   Associate this project with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
slides: ""
---

We figured that COVID-19 patients, including the asymptomatic can be identified using only cough recordings. We collected data of the cough recordings through various sources and the cough recordings are transformed with Mel Frequency Cepstral Coefficient and inputted into a Convolutional Neural Network (CNN)

We obtained accuracy of about 98%.