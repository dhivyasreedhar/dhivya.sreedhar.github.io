---
title: Spoken Digit Recognition
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
url_code: 'https://github.com/dhivyasreedhar/Spoken_Digit_Recognition'
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
Classification Methods for Audio MNIST Dataset

Dataset consists of recordings of spoken digits in wav files at 8kHz. The recordings are trimmed so that they have near minimal silence at the beginnings and ends.

The Samples recorded by 4 speakers with English pronunciations and there are totally 2,000 recordings (50 of each digit per speaker) in the dataset.

Files are named in the following format: {digitLabel}{speakerName}{index}.wav Example: 7_jackson_32.wav