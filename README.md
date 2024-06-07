# Intelligent Systems for Pattern Recognition
Solutions to the assignments from the Intelligent Systems for Pattern Recognition course \
Academic Year: 2023/24, University of Pisa

## Midterm 1: Continous Wavelet Decomposition (Assignment 3)

It contains accellerometer timeseries for 15 participants performing 7 different physical activities.
For this assignement focus on a single participant (of your choice) and study its 7 different activities 
using the Continous Wavelet Decomposition (CWD) approach discussed during the lectures. It suffices to compare the 
CWD visually and report you considerations on similarities and differences between the activities.

[DATASET](https://www.kaggle.com/datasets/imsparsh/single-chestmounted-accelerometer)


## Midterm 2: 

Fit an Hidden Markov Model to the data in DSET1: it is sufficient to focus on a single column of the dataset of your choice 
(i.e. choose one of the sensors available and focus on analysis that single sensor). 
Experiment with training  HMMs with two different choices of the emission distribution and confront the results.
Experiment also with HMMs with a varying number of hidden states (e.g. at least 2, 3 and 4) 
and identify what is the best choice according to your own reasoning. 

Once you have identified the best HMM configuration (emissions and number of states), choose a reasonably sized subsequence 
(e.g. last 25% of the timeseries) and compute the optimal assignement using two methods: i) Viterbi (true optimal) and ii) 
best state according to the hidden state posterior (very local decision). Then plot the timeseries data highlighting 
(e.g. with different colours) the hidden state assigned to each timepoint by the Viterbi algorithm and the posterior method.  
Discuss the results.

[DSET1 (Image processing)](www.kaggle.com/datasets/ztaihong/weizmann-horse-database/data)


## Midterm 3: 

Train 1 denoising and 1 contractive autoencoder on the MNIST dataset.
It is up to you to decide how many layers and neurons in each layer and how many layers you want in the deep autoencoder.
Show an accuracy comparison between the different autoencoders.

Then, experiment with what happens if you feed the autoencoders with a random noise image and then you apply
the iterative gradient ascent process described in the lecture to see if the reconstruction converges to the data manifold.
Confront the reconstructions created by the 2 different models and comment on the results.

[DATASET (Image processing: MNIST)](http://yann.lecun.com/exdb/mnist/)

