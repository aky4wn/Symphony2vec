# Symphony2vec
Duke ECE 590 Final Project: Learning Musically Meaningful Embeddings for Orchestral Audio Data


## Abstract

Algorithmic composition is the use of statistical and machine learning models to generate new music
and has received an increase in attention recently due to advances in deep learning. However, there is
currently no standard embedding approach for audio music data, which is a necessary prior step for
successful generative modeling. The goal of this project is to develop a musically meaningful latent
representation of orchestral audio recordings that could be used in later generative modeling tasks.
We explore the use of adversarially learned inference models to learn this embedding and compare
to baseline approaches. To my knowledge, this is some of the first work focusing on learning an
embedding for orchestral audio data The learned embeddings are evaluated on a downstream task of
composer classification. We find that the adversarially learned inference models do not outperform
baseline approaches on this classification task, but are able to recover some high-level musically
meaningful features in the latent space. Overall, learning a meaningful embedding for audio data
remains an open problem and a challenging task.
