# Pneumonia Detection Using Convolutional Neural Networks

```
S. Shah, H. Mehta and P. Sonawane, "Pneumonia Detection Using Convolutional Neural Networks," <br />
2020 Third International Conference on Smart Systems and Inventive Technology (ICSSIT), Tirunelveli, India, 2020, pp. 933-939 <br />
doi: 10.1109/ICSSIT48917.2020.9214289.
https://ieeexplore.ieee.org/abstract/document/9214289
```

## Overview of the Project <br />

Pneumonia is a fatal disease that majorly affects the elderly and may sometimes prove to be life threatening. Early diagnosis of Pneumonia gains a paramount importance for saving many human lives. 
This paper aims at the detection and classification of patients affected by Pneumonia based on their chest X-rays. <br />

A convolutional neural network is employed from scratch to make the above diagnosis and yield highly accurate results. Deep Learning models automate the process and ensure speedy, adroit, and adept results when provided with X-rays of patients.<br />

The classification occurs after the image is fed through a series of convolutional and max pooling layers that are activated by using the ReLU activation function that is subsequently fed into the neurons present in the dense layers and finally, the output neuron is activated by the sigmoidal function. <br />
The accuracy increases as the model trains and decreases the loss simultaneously. Overfitting is prevented by implementing data augmentation before fitting the model. <br />

Thus, efficient, and cogent results are obtained by the proposed deep learning models to classify the chest X-rays for the detection of pneumonia.

## Getting Started 

We mostly use Python in the project and hence, we used libraries that can be installed using - <br />
```
pip install tensorflow
pip install torch
pip install keras
pip install matplotlib
pip install sklearn
pip install numpy
pip install os
```

## Proposed Architecture

We propose the following architecture of CNN to analyze the X-ray data - <br />
![CNN Model](https://github.com/HeeketMehta/Pneumonia-Detection-Project/blob/master/OUTPUT/CNN%20Model.png)
<br />


## Deep Learning Model Summary


![Model Summary](https://github.com/HeeketMehta/Pneumonia-Detection-Project/blob/master/OUTPUT/model_summary.png)<br />

## Deep Learning Results

The results - in terms of validation and training curves are as follows - 
![Plots of val, training](https://github.com/HeeketMehta/Pneumonia-Detection-Project/blob/master/OUTPUT/pneumonia_val_train.png)<br />

The epoch results are -
![Epoch_results](https://github.com/HeeketMehta/Pneumonia-Detection-Project/blob/master/OUTPUT/25%20epoch%2016-32-64.JPG)<br />


## Conclusion
Please check out the paper we published at the following URL - 
```
https://ieeexplore.ieee.org/abstract/document/9214289
```
We really appreciate your interest

## Authors
```
Heeket Mehta
Shanay Shah
```

## Mentorship -
```
Prof. Pankaj Sonawane
```





