---
layout: post
title: "Neural machine translation"
description: "Guide to learn Neural machine Translation basics"
category: articles
tags: [python, machine-learning,Recurrent-Neuralnet,seq2seq]
comments: true
---

This is my very first post on this blog. I decided to write about something exciting and decided on Neural machine translation.

Neural Machine Translation is a hot topic in the Software industry today. This basically deals with translation of Texts from one language to another, i.e translation.

Language translation is approximately 40Billion Dollars industry, which is growing in demands in different parts of the world especially in Asia. It really helps in E-commerce, Social media , Tourism etc.

You might be familiar with machine translation systems already. Google translate is one example. You must have also seen translation option in Instagram and Facebook also. 

In this series of post , I plan to analyse machine learning techniques that helps in translation of texts using neural networks.


## Sequence to Sequence Model.

Sequence to Sequence model is one the highly successful neural net model used in Neural Machine translation.In short let's call it seq2seq model. 

The basic intuition of the seq2seq model is to find the next sequence with highest probability.

Just like CNN(Convolution Neural Network) is used for Image Recognition, RNN is the goto model when it comes to text generation.


In seq2seq model , we having 2 RNN based units. 
1)Encoder 
2)Decoder

Let's assume a usecase in which we want to translate a french sentence to English sentence.
