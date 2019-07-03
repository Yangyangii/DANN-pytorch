# **DANN (Domain Adaptation Neural Network)-pytorch**

### Paper: [Domain-Adversarial Training of Neural Networks](https://arxiv.org/pdf/1505.07818.pdf)

<img src="/asssets/DANN.JPG" width="400" height="200" />


## **Prerequisite**

- python 3.7 (Anaconda)

- pytorch >= 1.0

- torchvision >= 0.2.2


## **Dataset**

- SVHN(Source dataset), MNIST(Target dataset)

- Download from torchvision


## **Description**

- DANN.ipynb : DANN model and training algorithm

- NN.ipynb : Baseline model and training algorithm to compare with DANN

- The models were trained by 20~30 epochs respectively

- You can see the graphs of loss and accuracy in ipynb


- **Implementation and Result**
>- GRL (Gradient Reversal Layer)
>- 3 Modules (Feature extractor, Classifier, Discriminator)
>- Data preprocessing (Resize 28x28, gray scale, normalization [-1, 1], )
>- 2 Datasets (SVHN, MNIST)
>- Test Accuracy (on MNIST test set)
>>- **DANN: 70.64 %**
>>- Baseline model (Source only model): 57.80 %



<img src="/asssets/acc.jpg" width="300" height="200" />

