# Noisy-Labels-with-Bootstrapping
Keras implementation of Training Deep Neural Networks on Noisy Labels with Bootstrapping, Reed et al. 2015

## MNIST with noisy Labels
Below are the results of experiments from the original paper using MNIST.

![alt text](https://github.com/dwright04/Noisy-Labels-with-Bootstrapping/blob/master/Reed_et_al_figure_2.png)

---

### Open questions for reproducing results
* What data is the classification accuracy in Figure 2. measured on?
* How do they determine when to stop training?
* What is the mini-batch size?

Training for 500 epochs on 50000 examples with noise fraction of 0.3 achieves 99.93% classification accuracy measured on the training set with noisy labels.  This is higher than the equivalent result in Figure 2. from the paper shown above.

## Replicated MNIST with noisy labels results
![alt text](https://github.com/dwright04/Noisy-Labels-with-Bootstrapping/blob/master/replicated_results.png)
