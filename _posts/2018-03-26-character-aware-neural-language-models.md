---
layout: post
share: true
title: Character-Aware Neural Language Models
date: 2018-03-26 16:44:29 +0000
author:
  name: Jai Agarwal
  email: f2014428@pilani.bits-pilani.ac.in
categories:
- Natural Language Processing
tags:
- Medium
- Brownie Points
---
**Abstract:** We describe a simple neural language model that relies only on character-level inputs. Predictions are still made at the word-level. Our model employs a convolutional neural network (CNN) and a highway network over characters, whose output is given to a long short-term memory (LSTM) recurrent neural network language model (RNN-LM). On the English Penn Treebank the model is on par with the existing state-of-the-art despite having 60% fewer parameters. On languages with rich morphology (Arabic, Czech, French, German, Spanish, Russian), the model outperforms word-level/morpheme-level LSTM baselines, again with fewer parameters. The results suggest that on many languages, character inputs are sufficient for language modeling. Analysis of word representations obtained from the character composition part of the model reveals that the model is able to encode, from characters only, both semantic and orthographic information.

**Paper Link:** [https://arxiv.org/pdf/1508.06615.pdf](https://arxiv.org/pdf/1508.06615.pdf "https://arxiv.org/pdf/1508.06615.pdf")

**Task**: Implement the LSTM-Char-Small (i.e., the small architecture for character inputs) architecture in Python using Tensorflow, Pytorch, MXNet or NumPy. No need to implement hierarchical softmax. And, highway network layer is optional.

**Brownie Points**: Add a highway networks.