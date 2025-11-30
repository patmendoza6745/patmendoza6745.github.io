---
title: "Can Transformers Break Encryption Schemes via In-Context Learning?"
collection: publications
category: preprint
permalink: /publication/transformers-break-encryption-2025
date: 2025-08-13
venue: ''
authors: 'Jathin Korrapati*, Patrick Mendoza*, Aditya Tomar*, Abein Abraham*'
header:
  teaser: transformers-break-encryption.png
paperurl: 'https://arxiv.org/pdf/2508.10235'
bibtexurl: 'https://patmendoza6745.github.io/files/transformers-break-encryption.bib'
---

## Abstract

In-context learning (ICL) has emerged as a powerful capability of transformerbased language models, enabling them to perform tasks by conditioning on a small number of examples presented at inference time, without any parameter updates. Prior work has shown that transformers can generalize over simple function classes like linear functions, decision trees, even neural networks, purely from context,
focusing on numerical or symbolic reasoning over underlying well-structured functions. Instead, we propose a novel application of ICL into the domain of cryptographic function learning, specifically focusing on ciphers such as monoalphabetic substitution and Vigenère ciphers, two classes of private-key encryption schemes. These ciphers involve a fixed but hidden bijective mapping between
plain text and cipher text characters. Given a small set of (cipher text, plain text) pairs, the goal is for the model to infer the underlying substitution and decode a new cipher text word. This setting poses a structured inference challenge, which is well-suited for evaluating the inductive biases and generalization capabilities of transformers under the ICL paradigm. 