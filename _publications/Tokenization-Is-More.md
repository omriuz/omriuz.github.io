---
title: "Tokenization Is More Than Compression"
authors_1: "Craig W. Schmidt, Varshini Reddy, Haoran Zhang, Alec Alameddine, "
authors_2: "Yuval Pinter, Chris Tanner"
collection: publications
category: Preprints
permalink: /publication/Tokenization-Is-More
# excerpt: 'This paper is about the number 2. The number 3 is left for future work.'
# date: 2024-04-28
# venue: 'Journal 1'
# slidesurl: 'http://academicpages.github.io/files/slides2.pdf'
paperurl: 'https://arxiv.org/abs/2402.18376'
authors: 'Craig W. Schmidt, Varshini Reddy, Haoran Zhang, Alec Alameddine, Omri Uzan, Yuval Pinter, Chris Tanner'
---

Tokenization is a foundational step in Natural Language Processing (NLP) tasks, bridging raw text and language models. Existing tokenization approaches like Byte-Pair Encoding (BPE) originate from the field of data compression, and it has been suggested that the effectiveness of BPE stems from its ability to condense text into a relatively small number of tokens. We test the hypothesis that fewer tokens lead to better downstream performance by introducing PathPiece, a new tokenizer that segments a document's text into the minimum number of tokens for a given vocabulary. Through extensive experimentation we find this hypothesis not to be the case, casting doubt on the understanding of the reasons for effective tokenization. To examine which other factors play a role, we evaluate design decisions across all three phases of tokenization: pre-tokenization, vocabulary construction, and segmentation, offering new insights into the design of effective tokenizers. Specifically, we illustrate the importance of pre-tokenization and the benefits of using BPE to initialize vocabulary construction. We train 64 language models with varying tokenization, ranging in size from 350M to 2.4B parameters, all of which are made publicly available.