---
layout: default
title: Resources
permalink: /2026/resources/
tagline: 2026
---

# Word embedding models

[Gensim](https://github.com/piskvorky/gensim#documentation) is a Python library for topic modelling, document indexing and similarity retrieval with large corpora. It supports and offers various embedding models. 

There are various pretrained embedding models that you can download, some are available only for English, others for many more languages; they also vary in the kinds of text used for training (eg, wikipedia, social media, etc). Here's a non-exhaustive list:

* [GloVe](https://nlp.stanford.edu/projects/glove/) - pretrained embeddings whose training objective combines global matrix factorization and local context windows
* [fasttext](https://fasttext.cc/) - pretrained embeddings for some 150 languages (some fasttext models are based on subword units)
* [ConceptNet Numberbatch](https://github.com/commonsense/conceptnet-numberbatch) - embeddings enhanced with semantic knowledge from the ConceptNet knowledge graph
* [Kyubyong Park’s repository](https://github.com/Kyubyong/wordvectors) - pretrained word2vec embeddings in some 30 languages

# Text analysis packages

* [TextDescriptives](https://hlasse.github.io/TextDescriptives/) - syntactic complexity and coherence measures
* [Detoxify](https://github.com/unitaryai/detoxify) - tools for handling toxicity; this tool is not as lightweight as others, for it is based on large pretrained encoders
* [scireadability](https://pypi.org/project/scireadability/), [textstat](https://github.com/shivam5992/textstat) and [textcomplexity](https://github.com/tsproisl/textcomplexity) - readability and grade level (with some support beyond English)
* [Elfen](https://elfen.readthedocs.io/en/latest/) - readability metrics, incl. semantic ones (e.g. number of hedges), sentiment, emotion (e.g. valence, arousal, dominance) and psycholinguistic (e.g. concreteness, iconicity) features
* [TRUNAJOD](https://trunajod20.readthedocs.io/en/latest/) - text complexity including syntactic, semantic, and discourse levels (built on spaCy)
* [spaCy](https://spacy.io) - broad range of NLP tools
* A few tools based on pretrained encoders (eg, BERT/RoBERTa): [emotion](https://huggingface.co/AnasAlokla/multilingual_go_emotions), [politeness](https://huggingface.co/Intel/polite-guard) and [sentiment](https://huggingface.co/cardiffnlp/twitter-xlm-roberta-base-sent)
