---
title: "Greed is all you need: An evaluation of tokenizer inference methods"
authors_1: ""
authors_2: "Craig W. Schmidt, Chris Tanner, Yuval Pinter"
collection: publications
category: conferences
permalink: /publication/greed
# excerpt: 'This paper is about the number 3. The number 4 is left for future work.'
date: 2024-08-12
venue: 'ACL, Outstanding Paper Award, Senior Area Chair Paper Award, Oral presentation'
# slidesurl: 'http://academicpages.github.io/files/slides3.pdf'
paperurl: 'https://aclanthology.org/2024.acl-short.73/'
# citation: 'Your Name, You. (2015). &quot;Paper Title Number 3.&quot; <i>Journal 1</i>. 1(3).'
---


While subword tokenizers such as BPE and WordPiece are typically used to build vocabularies for NLP models, the method of decoding text into a sequence of tokens from these vocabularies is often left unspecified, or ill-suited to the method in which they were constructed. We provide a controlled analysis of seven tokenizer inference methods across four different algorithms and three vocabulary sizes, performed on a novel intrinsic evaluation suite we curated for English, combining measures rooted in morphology, cognition, and information theory. We show that for the most commonly used tokenizers, greedy inference performs surprisingly well; and that SaGe, a recently-introduced contextually-informed tokenizer, outperforms all others on morphological alignment.