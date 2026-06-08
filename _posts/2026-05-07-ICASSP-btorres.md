---
layout: post
title: "Learning Linearity in Audio Consistency Autoencoders via Implicit Regularization"
date: 2026-05-07 16:00:00 +0200
category: Publication
author: gmeseguerbrocal
readtime: 1
domains: 
people:
 - btorres
 - mmoussallam
 - gmeseguerbrocal
publication_type: conference
publication_title: "Learning Linearity in Audio Consistency Autoencoders via Implicit Regularization"
publication_year: 2026
publication_authors: Bernardo Torres, Manuel Moussallam, Gabriel Meseguer-Brocal
publication_conference: ICASSP
publication_preprint: "https://arxiv.org/pdf/2510.23530"
---
Audio autoencoders learn useful, compressed audio representations, but their non-linear latent spaces prevent intuitive algebraic manipulation such as mixing or scaling. We introduce a simple training methodology to induce linearity in a high-compression Consistency Autoencoder (CAE) by using data augmentation, thereby inducing homogeneity (equivariance to scalar gain) and additivity (the decoder preserves addition) without altering the model’s architecture or loss function. When trained with our method, the CAE exhibits linear behavior in both the encoder and decoder while preserving reconstruction fidelity. We test the practical utility of our learned space on music source composition and separation via simple latent arithmetic. This work presents a straightforward technique for constructing structured latent spaces, enabling more intuitive and efficient audio processing.