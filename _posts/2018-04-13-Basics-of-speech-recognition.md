---
title:  "[Part 1] Speech Recognition : A review"
date:   2018-04-13 15:04:23
categories: [deep learning, speech recognition]
tags: [speech, asr, dnn, hmm, gmm, mfcc]
---

[Speech recognition][wiki]  is the inter-disciplinary sub-field of computational linguistics that develops methodologies and technologies that enables the recognition and translation of spoken language into text by computers. It is also known as "automatic speech recognition" (ASR), "computer speech recognition", or just "speech to text" (STT). It incorporates knowledge and research in the linguistics, computer science, and electrical engineering fields. The achievement of high accuracy in converting speech to text has led to increased creation and usage of Speech recognition systems like Amazon Alexa, Google Now, Apple Siri and Microsoft Cortana. Hence it is important to understand the underlying technologies that make speech recognition possible in todays world. Here in this blog post

### Topic covered :

* History
* Human Speech Generation and Perception
* Phonetic Units
* Feature Extraction
  - mfcc (Mel Frequency Cepstral Coefficients)
  - lpcc (Linear Prediction Cepstral Coefficients)
  - plp
* Acoustic Modelling
  - GMM-HMM
  - DNN-HMM
* Language Modelling
  - n-gram
  - Neural Network based
  - LSTM based Modelling
* Training
  - EM Algorithm (Baum Welsh)
* Decoding
  - Viterbi Algorithm
  - BEAM search
* Isolated Word Recognition
* Continuous Word Recognition
* LVCSR
* CNN based Speech Recognition
* CTC Cost function
* RNN LSTM based Speech Recognition
* WaveNets  

More recent developments in speech recognition are in deep learning with CNN, RNN etc.

## History

* 1960s Dynamic Time Warping (DTW)
* 1970s Hidden Markov Models
* 1986 Multilayer Perception
* Speech Recognition with Neural Networks (1987 - 1995)
* GMM based Speech Recognition systems (1995 - 2009)
* Neural Network for Feature Extraction (2002)
* Deep Networks (Hinton, 2002)
* Deep Networks for Speech Recognition
* RNN for Speech Recognition (1990, 2012 - )


[wiki]: https://en.wikipedia.org/wiki/Speech_recognition
