---
title: "Audio signal one-class classification over the years"
date: 2022-07-16T20:04:50+02:00
draft: false
---
The first time I encountered the one-class classification of audio di was back in 2009. Back then, I wasn't too keen to try machine learning approaches to the problem, so I stuck to what was familiar to me: convolution. This problem was different from voice recognition because humans can produce a wider range of sounds than the ones I was trying to detect, namely sounds produced by certain insect species.

Some alternatives were presented to me then:
* Window functions (e.g. Hamming window)
* Matched filter
* Wiener filter
* Dynamic time warping
* Matlab's MA Toolbox audio similarity measure
* Support vector machine
* Blind source separation (e.g. Independent component analysis)
* Hidden Markov Model
* Naive Bayes Classifier
* Autocorrelation via recursive least squares filter

Then in 2022 I finally came accross a solution involving neural networks: recurrent variants (LSTM/GRU) that can be paired with one or two convolutional layers (CNN), with the CNN layer operating on a few frames of FFT-transformed audio.