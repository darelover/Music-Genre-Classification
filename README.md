# Music-Genre-Classification

This is a Keras implementation to classify genre of audio files from [GTZAN Genre Collection](http://marsyas.info/downloads/datasets.html) using Neural Networks. 

## Todo:
- [ ] Instead of applying dense neural networks, convert audio files to spectrogram images and apply cnn model
- [ ] Model is overfitting, therefore, apply regularisation 
- [ ] Other dataset that can be used is [Audio set](https://research.google.com/audioset//ontology/music_genre_1.html) dataset made available by Google Inc.

## References:
1. [Dropout: A Simple Way to Prevent Neural Networks from
Overfitting](http://www.cs.toronto.edu/~rsalakhu/papers/srivastava14a.pdf)
2. [
Batch Normalization: Accelerating Deep Network Training by Reducing Internal Covariate Shift](https://arxiv.org/abs/1502.03167)
3. This notebook uses [librosa](http://conference.scipy.org/proceedings/scipy2015/pdfs/brian_mcfee.pdf) library to extract features features from audio clips.
4. [Medium blog by Parul Pandey](https://towardsdatascience.com/music-genre-classification-with-python-c714d032f0d8)
