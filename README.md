# Analyzing the Vulnerability of Machine Learning Models against Membership Inference Attacks

In this project, we are implementing the membership inference attack on a neural network model built on the Fashion MNIST image dataset. 
For the implementation of this attack, we are following the Shadow Model Training technique proposed by Shokri et al.  

## Team
|Student name| CCID |
|------------|------|
|Chirag Daryani   |  cdaryani    |
|Karan Chadha   |  kchadha1    |

## Code Files

* `Attack1-TrainingSize_and_attack model_variation.ipynb`

Implementation of complete membership attack, analysis of change in training size of target model and change in attack model architecture

* `Attack2-No_of_Classes_variation.ipynb`

Analysis of change in number of output classes of the target model.

* `Attack3-Overfitting_and_Dropout.ipynb`

Analysis of effect of overfitting and regularization techniques like dropout.

**All these notebooks can be executed on Google Colab**

## References


https://github.com/cloudxlab/ml/blob/master/projects/Fashion-MNIST/Fashion-MNIST-DL-Keras.ipynb

https://github.com/csong27/membership-inference

https://github.com/Jongho0/ml_mbr_inf

https://github.com/BielStela/membership_inference

https://github.com/mahdiabdollahpour/Security-and-Privacy-in-Machine-Learning/blob/main/Membership%20Inference%20Attack/Membership%20Inference%20Attack.ipynb

https://cloudxlab.com/blog/fashion-mnist-using-deep-learning-with-tensorflow-keras/

https://machinelearningmastery.com/how-to-develop-a-cnn-from-scratch-for-fashion-mnist-clothing-classification/

https://machinelearningmastery.com/dropout-for-regularizing-deep-neural-networks/
