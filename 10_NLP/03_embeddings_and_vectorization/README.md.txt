# Pre-trained Word Embedding Models

This repository uses pre-trained word embedding models as benchmarks for NLP experiments, tutorials, and future extensions .present in the folder `pre-trained-model. Pre-trained embeddings capture rich semantic and syntactic relationships learned from large corpora and are commonly used as strong baselines in natural language processing tasks.

# GloVe (Global Vectors for Word Representation)

**Model:** glove.6B.300d.txt

**Dimensions:** 300

**Training corpus:** Wikipedia 2014 + Gigaword 5 (6B tokens)

**Description:** GloVe embeddings are trained using global word co-occurrence statistics, combining the advantages of count-based and predictive models. They are lightweight, easy to load, and widely used in NLP research and education.

Source:
https://www.kaggle.com/datasets/serquet/word2vecglove6b300d

# Google Word2Vec

**Model:** GoogleNews-vectors-negative300.bin

**Dimensions:** 300

**Training corpus:** Google News (~100B words)

**Description:** Word2Vec embeddings are trained using a neural predictive model (Skip-gram with Negative Sampling). This model is known for capturing strong semantic relationships and analogies.

Source:
https://drive.google.com/file/d/0B7XkCwpI5KDYNlNUTTlSS21pQmM

# Usage

These embeddings are used throughout the repository for:

NLP benchmarking

Demonstrating word similarity and analogy tasks

Comparing classical embeddings with modern approaches (e.g., contextual embeddings)

Educational tutorials on word representations

**Note:** The embedding files are large and may not be included directly in the repository. Please download them from the original sources above before running the notebooks or scripts.