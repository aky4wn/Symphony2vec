## PyTorch Code for Project

- ``Audio_Pre-Processing.ipynb`` loads the audio files, splits them into 10 s chunks and transforms them into the spectrogram, chromagram and MFCC representations
- ``EDA.ipynb`` performs some basic exploratory visualization
- ``FF-Baseline.ipynb`` explores basic fully connected, feed forward architectures as a classification baseline
- ``CNNs-Baseline.ipynb`` and ``LSTM-Baseline.ipynb`` explore basic CNN and LSTM, respectively, baseline classification architectures
- ``AE_CAE_PCA.ipynb`` explores basic embedding methods: Autoencoders, Contractive Autoencoders and PCA
- ``VAE.ipynb`` explores VAE baselines for encoding
- ``ALI-spec-32x32-40.ipynb``, ``ALI-spec-32x32-128.ipynb`` and ``ALI-spec-32x32-256.ipynb`` are the main notebooks for exploring Adversarially Learned Inference (https://arxiv.org/abs/1606.00704), with 40, 128 and 256 dimenisonal latent spaces, respectively



Adversarially Learned Inference code is following https://github.com/9310gaurav/ali-pytorch.
