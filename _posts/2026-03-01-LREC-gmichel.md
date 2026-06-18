---
layout: post
title: "S-VoCAL: A Dataset and Evaluation Framework for Inferring Speaking Voice Character Attributes in Literature"
date: 2026-03-01 10:00:00 +0200
category: Publication
author: gmichel
readtime: 1
domains: 
 - NLP
people:
 - gmichel
 - eepure
publication_type: conference
publication_title: "S-VoCAL: A Dataset and Evaluation Framework for Inferring Speaking Voice Character Attributes in Literature"
publication_year: 2026
publication_authors: Abigail Berthe-Pardo, Gaspard Michel, Elena V. Epure, Christophe Cerisara
publication_conference: LREC
publication_code: "https://github.com/AbigailBerthe/S-VoCAL"
publication_preprint: "https://arxiv.org/pdf/2603.00958"
---

With recent advances in Text-to-Speech (TTS) systems, synthetic audiobook narration has seen increased interest, reaching unprecedented levels of naturalness. However, larger gaps remain in synthetic narration systems' ability to impersonate fictional characters, and convey complex emotions or prosody. A promising direction to enhance character identification is the assignment of plausible voices to each fictional characters in a book. This step typically requires complex inference of attributes in book-length contexts, such as a character's age, gender, origin or physical health, which in turns requires dedicated benchmark datasets to evaluate extraction systems' performances. We present S-VoCAL (Speaking Voice Character Attributes in Literature), the first dataset and evaluation framework dedicated to evaluate the inference of voice-related fictional character attributes. S-VoCAL entails 8 attributes grounded in sociophonetic studies, and 952 character-book pairs derived from Project Gutenberg. Its evaluation framework addresses the particularities of each attribute, and includes a novel similarity metric based on recent Large Language Models embeddings. We demonstrate the applicability of S-VoCAL by applying a simple Retrieval-Augmented Generation (RAG) pipeline to the task of inferring character attributes. Our results suggest that the RAG pipeline reliably infers attributes such as Age or Gender, but struggles on others such as Origin or Physical Health.