---
layout: post
kind: project
title:  Visual Concept Vocabulary for GANs
authors:
    - Sarah Schwettmann
    - Evan Hernandez
    - David Bau
    - Samuel Klein
    - Jacob Andreas
    - Antonio Torralba
conference: ICCV
year: 2021
paper: https://arxiv.org/abs/2110.04292
website: https://visualvocab.csail.mit.edu/
code: https://github.com/schwettmann/visual-vocab
thumbnail: assets/images/2021-visual-vocab.gif
thumbnail_alt: visual concept vocabulary
thumbnail_caption: "+snow, +clouds"
---
GANs sometimes encode visual concepts in their latent space as <b>linear directions</b>.
We construct a <b>visual concept vocabulary</b> for pretrained GANs, consisting of latent directions
and free-form language descriptions of the changes they induce. We then distil the vocabulary into simpler,
one-word visual concepts (e.g., <i>snow</i> or <i>clouds</i>).
