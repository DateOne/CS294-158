## Logistics
## Motivation
### What is unsupervised learning?
1. easy way: annotating data is extausting;
2. two general approaches: generative models (probability distribution); self-supervised learning (puzzles are rendered that require semantic understanding);
3. Geoffrey Hindon's synapses metaphor;
4. Yann LeCun's cake metaphor;
5. **intelligence is all about compression**;
6. applications;
* in BigGAN, we are inspired that latents could be used for other things in the future; 
## Likelihood-based models: autoregressive models
### Motivation
1. some problems: generating data; compressing data; anomaly detection;
* generating and compressing are actually same;
2. what is likelihood-based model: joint distribution (what is distribution);
### Histogram
1. histogram model;
2. failure in high dimnensions;
* function approximization (the parameter space indexing into the space of probability distributions);
### Likelihood-based models part1: Autoregressive models
1. Fitting into distribution: maximum likelihood, SGD (averages);
2. Bayes net;
3. a toy autoregressive model (a histogram and a multilayer perceptron);
4. RNN autoregressive models (char rnn);
4. masking-based autoregressive models: parallelized computation (rnns are slow); masked autoencoder for distribution estimation (MADE); masked temporal (1D) 
Convolution; WaveNet; masked spatial (2D) convolutional (PixelCNN; Gated PixelCNN; PixelCNN++).
