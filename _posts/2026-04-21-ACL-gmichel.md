---
layout: post
title: "Computational Narrative Understanding for Expressive Text-to-Speech"
date: 2026-04-21 10:00:00 +0200
category: Publication
author: gmichel
readtime: 1
domains: 
 - NLP
people:
 - gmichel
 - eepure
publication_type: conference
publication_title: "Computational Narrative Understanding for Expressive Text-to-Speech"
publication_year: 2026
publication_authors: Gaspard Michel, Elena V. Epure, Christophe Cerisara
publication_conference: ACL
publication_code: "https://github.com/deezer/libriquote"
publication_preprint: "https://arxiv.org/pdf/2509.04072"
---

Recent advances in text-to-speech (TTS) have been driven by large, multi-domain speech corpora, yet the expressive potential of audiobook data remains underexamined. We argue that human-narrated audiobooks, particularly fictional works, contain rich and diverse prosodic cues arising from the natural alternation between neutral narration and expressive character dialogue. Building from this observation, we introduce LibriQuote, a large-scale 5.3K hours of expressive speech drawn from character quotations. Each quote is supplemented with contextual pseudo-labels for speech verbs and adverbs that characterize the intended delivery of direct speech (e.g., "he whispered softly"). We found that fine-tuning a flow-matching model on LibriQuote yields substantial improvements in expressivity and intelligibility, while training from scratch enhances expressiveness of an autoregressive TTS model. Benchmarking on LibriQuote-test highlights significant variability across systems in generating expressive speech. We publicly release the dataset, code, and evaluation resources to facilitate reproducibility. Audio samples can be found at this [url](https://libriquote.github.io/).