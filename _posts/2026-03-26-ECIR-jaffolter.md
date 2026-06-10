---
layout: post
title: "Scalable Music Cover Retrieval Using Lyrics-Aligned Audio Embeddings"
date: 2026-03-26 18:00:00 +0200
category: Publication
author: eepure
readtime: 1
domains: 
 - MIR
people:
 - eepure
 - gmeseguerbrocal
 - bmartin
publication_type: conference
publication_title: "Scalable Music Cover Retrieval Using Lyrics-Aligned Audio Embeddings"
publication_year: 2026
publication_authors: Affolter, Joanne and Martin, Benjamin and Elena V. Epure and Gabriel Meseguer-Brocal and Kaplan, Frederic
publication_conference: European Conference on Information Retrieval
publication_code: "https://github.com/deezer/LIVI-Lyrics-Informed-Version-Identification"
publication_preprint: "https://arxiv.org/abs/2601.11262"
---

Music Cover Retrieval, also known as Version Identification, aims to recognize distinct renditions of the same underlying musical work, a task central to catalog management, copyright enforcement, and music retrieval. State-of-the-art approaches have largely focused on harmonic and melodic features, employing increasingly complex audio pipelines designed to be invariant to musical attributes that often vary widely across covers. While effective, these methods demand substantial training time and computational resources. By contrast, lyrics constitute a strong invariant across covers, though their use has been limited by the difficulty of extracting them accurately and efficiently from polyphonic audio. Early methods relied on simple frameworks that limited downstream performance, while more recent systems deliver stronger results but require large models integrated within complex multimodal architectures. We introduce LIVI (Lyrics-Informed Version Identification), an approach that seeks to balance retrieval accuracy with computational efficiency. First, LIVI leverages supervision from state-of-the-art transcription and text embedding models during training to achieve retrieval accuracy on par with--or superior to--harmonic-based systems. Second, LIVI remains lightweight and efficient by removing the transcription step at inference, challenging the dominance of complexity-heavy pipelines.
