# repo for CAP 5610 Machine Learning

### Common ML problems, overview of (a) supervised, (b) unsupervised, and (c) reinforcement learning

  - [1 Slides](https://github.com/schneider128k/machine_learning_course/blob/master/slides/1_slides.pdf)

### ML terminology, linear regression, training & loss, gradient descent, stochastic gradient descent

  - [2 Slides](https://github.com/schneider128k/machine_learning_course/blob/master/slides/2_slides.pdf)

### Linear regression using the normal equation - numpy implementation 

  To understand the mathematics underlying the normal equation, read the following materials:

  - [Chapter 2 Linear Algebra](https://www.deeplearningbook.org/contents/linear_algebra.html)
  
  - [Chapter 4 Numerical Computation, Section 4.3 Gradient-Based Optimization](https://www.deeplearningbook.org/contents/numerical.html) 
  
  - [Chapter 5 Machine Learning Basics, Subsection 5.1.4 Example: Linear Regression](https://www.deeplearningbook.org/contents/ml.html)
  
  - [Additional materials: proof of convexity of MSE and computation of gradient of MSE](https://github.com/schneider128k/machine_learning_course/blob/master/slides/linear_regression.pdf)
  
  - [Colab notebook for solving linear regression using normal equation](https://colab.research.google.com/drive/1J7yct9aGfhtfXw8n00Mq4R-xldSSM1WY)

### Effect of learning rate on gradient descent

  - [Colab notebook for experimenting with different learning rates](https://colab.research.google.com/drive/1eECClMU1r-Y9hzPnRw89__jC3nw3C-zD)
   
### Linear regression using gradient descent - numpy implementation

  - [Colab notebook for solving linear regression using gradient descent](https://colab.research.google.com/drive/1qBxfTPoNcSFvpwu1NDl1V6cHEqL3aQl-)

### Overview of TensorFlow and Keras

  - [3 Slides](https://github.com/schneider128k/machine_learning_course/blob/master/slides/3_slides.pdf)

  - [Anatomy of a neural network](https://github.com/schneider128k/machine_learning_course/blob/master/slides/anatomy_of_neural_network.md)

  - [4 Slides](https://github.com/schneider128k/machine_learning_course/blob/master/slides/4_slides.pdf)

### Keras examples

  - [Colab notebook for solving linear regression for artificial data set](https://colab.research.google.com/drive/1pOFL4Qm6WOn2Nxxy6_HteEqQMxStTwzs)
  
  - [Colab notebook for loading and exploring the MNIST digits data set](https://colab.research.google.com/drive/1HDZB0sEjhd0sdTFNCmJXvB8hYnE9KBM7)
  
  - [Colab notebook for classifying MNIST digits with dense layers and analyzing model performance](https://colab.research.google.com/drive/144nj1SRtSjpIcKZgH6-GPdA9bWkg68nh)
  
  - [Colab notebook for classifying MNIST fashion items with dense layers and analyzing model performance](https://colab.research.google.com/drive/1TTO7P5GTmsHhIt_YGqZYyw4KGBCnjqyW)

  - [Colab notebook for displaying CIFAR10 data set](https://colab.research.google.com/drive/1LZZviWOzvchcXRdZi2IBx3KOpQOzLalf)

### Generalization, overfitting, splitting data in train & test sets

  - [5 Slides](https://github.com/schneider128k/machine_learning_course/blob/master/slides/5_slides.pdf)
  
### Validation

  - [6 Slides](https://github.com/schneider128k/machine_learning_course/blob/master/slides/6_slides.pdf)

### Logistic regression, gradients for squared error and binary cross-entropy loss functions

  - [Logistic regression notes](https://github.com/schneider128k/machine_learning_course/blob/master/slides/logistic_regression.pdf)

### Softmax, categorical cross entropy loss, gradients

  - [Softmax, categorical cross entropy](https://github.com/schneider128k/machine_learning_course/blob/master/slides/softmax.pdf)
  
  - [Colab notebook for verifying formulas for partial derivatives with symbolic differentiation](https://colab.research.google.com/drive/1G8u6w3FFhZyb0nWfparVvn77DSjHyxEW)

### Sequential neural networks with dense layers

  - [Notes on forward propagation, backpropagation algorithm for computing partial derivatives wrt weights and biases](https://github.com/schneider128k/machine_learning_course/blob/master/slides/neural_networks.pdf)
  
  - [Code for creating sequential neural networks with dense layers and training them with backprop and mini-batch SGD](https://github.com/schneider128k/machine_learning_course/blob/master/code/neural_network.py); currently, code is limited to (1) mean squared error loss and (2) sigmoid activations.

### Deep learning for computer vision (convolutional neural networks)

  - [CNN slides](https://github.com/schneider128k/machine_learning_course/blob/master/slides/CNN_slides.pdf)
  
  TO DO: add note of preventing overfitting with data augmentation (also, add L2/L1 regularization and dropout earlier!)

  **Classification of MNIST digits and fashion items**

  - [Colab notebook for classifying MNIST digits with convolutional layers and analyzing model performance](https://colab.research.google.com/drive/1HA-PoWkxgYa37McvUrA_n609jkKT5F7m)
  
  - [Colab notebook for classifying MNIST fashion items with convolutional layers and anlyzing model performance](https://colab.research.google.com/drive/1eI47U0vW_5ok6rVvNuenXS2EkTbqxcCV)
  
   **Classification of cats and dogs**
   
   based on Chapter 5 *Deep learning for computer vision* of the book *Deep learning with Python* by F. Chollet
   
   - [training convnet from scratch](https://colab.research.google.com/drive/1Jem-Kw-1z3TyFpgVfkxmfapPkH7wxh00)
   
   - [training convnet from scratch, using data augmentation and dropout](https://colab.research.google.com/drive/1bOov0VTMHNP_zasrSVPrDdzI3MBMcxgW)
   
   - [using VGG16 conv base for fast feature extraction (data augmentation not possible), using dropout](https://colab.research.google.com/drive/1Vame3KCI2KtnTLXnTXK0ZRaT8YjRErGz)
   
   - [using VGG16 conv base for feature extraction, using data augmentation, not using dropout](https://colab.research.google.com/drive/1pRyVUWTWGVBsJUYiR8rGgBAMva2ICdmi)
   
   - [using VGG16 conv base for feature extraction, using data augmentation, not using dropout, fine-tuning](https://colab.research.google.com/drive/1F-RWvoxH8MmT7c1UmNy41iuOp-ejiLoF)
  
  TO DO: execute fine-tuning!
  
  --- 
    
 based on [Google ML Practicum: Image Classification](https://developers.google.com/machine-learning/practica/image-classification/)
    
  - [Colab notebook for training a convolutional neural network from scratch](https://colab.research.google.com/drive/1GCz7d32nfYTlY1paDk7-2oVw6E7HFK80)
   
  - [Colab notebook for training a CNN from scratch with data augmentation and dropout](https://colab.research.google.com/drive/1R67uzd5n_v2qnQh6klVCyBFCHTBRWZnF)
  
  - [Colab notebook for fine-tuning Google's Inception v3 model](https://colab.research.google.com/drive/1uVLIUWdT7--b59vM7NaSHkB-qFcu30jU)
  
 ---
  
### Deep learning for text and sequences (RNN, LSTM)

### Generative deep learning (VAE, GAN)

---

[Tools, additional materials](https://github.com/schneider128k/machine_learning_course/blob/master/tools_additional_materials.md)

