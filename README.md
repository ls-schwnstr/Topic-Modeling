# Topic-Modeling with Disneyland Reviews
This repository contains code and resources for conducting topic modeling on a dataset of Disneyland reviews. The project aims to extract meaningful topics from the reviews and gain insights into the key themes expressed by visitors.

## Overview

This project explores different topic modeling techniques applied to a corpus of Disneyland reviews. The dataset comprises textual reviews written by visitors, providing valuable feedback and opinions about their experiences at Disneyland.

## Techniques Used

The following topic modeling techniques are employed:

- LDA Modeling with Bag-of-Words (BoW) Corpus: Latent Dirichlet Allocation (LDA) is used to model topics using a Bag-of-Words representation of the reviews. This technique considers word frequencies in the corpus, disregarding word order.
- LDA Modeling with TF-IDF Corpus: Similar to the previous technique, LDA is applied for topic modeling, but using the Term Frequency-Inverse Document Frequency (TF-IDF) representation. TF-IDF adjusts word frequencies based on their importance in the entire corpus, giving more weight to meaningful and distinct words.
- Hierarchical Dirichlet Process (HDP) Modeling with Gensim: The HDP model, a Bayesian nonparametric approach, is employed for topic modeling. It automatically determines the number of topics in the corpus. The HDP model provided by the Gensim library is utilized to discover latent topics in the Disneyland reviews.
- Hierarchical Dirichlet Process (HDP) Modeling with Tomotopy: In addition to the Gensim library, the HDP model implementation in Tomotopy is explored. Tomotopy is an efficient and scalable library for topic modeling, offering various features and optimizations.
   
## Installation

Requirements: Python 3.7+

Required Packages can be retrieved from [requirements.txt](https://github.com/ls-schwnstr/Topic-Modeling/blob/main/requirements)

Required Dataset: can be downloaded from Kaggle [here](https://www.kaggle.com/datasets/arushchillar/disneyland-reviews)

The [Preprocessing](https://github.com/ls-schwnstr/Topic-Modeling/blob/main/requirements) must be executed first.
