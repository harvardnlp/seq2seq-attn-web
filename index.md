---
layout: default
title: Home
---


# OpenNMT

OpenNMT is a full-featured, open-source (MIT) neural machine translation system.

<img src="simple-attn.png" />


[Torch](http://torch.ch) implementation of a standard sequence-to-sequence model with (optional)
attention where the encoder-decoder are LSTMs. Also has the option to use characters
(instead of input word embeddings) by running a convolutional neural network followed by a
[highway network](http://arxiv.org/abs/1505.00387) over character embeddings to use as inputs.


