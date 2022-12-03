# Human Data Analytics
This repository is realized following the path of the course [Human Data Analytics](https://en.didattica.unipd.it/off/2022/LM/IN/IN2371/004PD/INP9087860/N0), which covers advanced and applied machine learning techniques, applied to real world problem within the human data domain. 

## Topics
### 1) Dimensionality reduction and clustering
_Tools:_
- Dimensionality reduction: PCA
- Unsupervised Clustering: K-means, SOM, GNG, DB-SCAN

_Applications:_ Electrocardiography (ECG) signal
  
### 2) Neural Networks
_Tools:_
- Feed Forward (FFNN), Convolutional (CNN)
- Recurrent Neural Networks (RNN)
- Residual Networks
- Implementation tricks: batch normalization, dropout, inception layers, attention mechanism, autoencoders
- Times series analysis: RNN, RNN+attention, transformer model

_Applications:_
- ECG signal
- Pulse oximeter (blood oxygenation)
- Speech analysis
- Inertial signal (motion analysis)
- Authentication, activity recognition (heterogeneous data)
- Medical images: lymphoma classification

## Laboratories
**[LAB 0](Lab_0_preparatory)** <br>
Preparatory material.


**[LAB 1](Lab_1)** <br>
**Title:** Machine learning tools for dimensionality reduction: PCA and clustering <br>
**Topics:** 
1. Python implementation (from scratch) of dimensionality reduction through principal component analysis (PCA).
2. Exploitation of the already implemented PCA algorithm (from the Python Scikit-learn library) for dimensionality reduction.
3. Implementation of dimensionality reduction based on K-means clustering.
4. Application of the implemented dimensionality reduction techniques to ECG signals acquired through the POLAR sensor and evaluation of their performance, both visually and by computing error metrics.

**[LAB 2](Lab_2)** <br>
**Title:** CNN for multi-class image classification <br>
**Topics:** 
1. Introduction to TensorFlow.
2. Implementation of a CNN through two different strategies: using the TensorFlow Keras Sequential and Model classes.
3. Implementation of the CNN training process through two different approaches: through the standard training methods in TensorFlow and implementing a custom training pipeline.
4. Implementation of an advanced training pipeline with the TensorFlow Dataset class (processing, caching, batching).
5. Application of the CNN to two hand signs recognition tasks.


**[LAB 3](Lab_3)** <br>
**Title:** CNN autoencoder <br>
**Topics:**
1. Implementation of the PCA (a simple autoencoder model) through FNN based encoder and decoder.
2. Introduction to transposed convolutional layers.
3. Implementation of an advanced autoencoder through CNNs for image encoding, i.e., dimensionality reduction.
4. Implementation of an image similarity algorithm based on the code from the encoder architecture and a KNN clustering.
5. Training of the autoencoder for image denoising.
6. Application of the techniques to images from the Malaria dataset.

**[LAB 4](Lab_4)** <br>
**Title:** Inception layer <br>
**Topics:** CNN-based Inception-v4 architecture for a multi-class classification task.
