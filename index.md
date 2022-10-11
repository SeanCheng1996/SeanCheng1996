# Sean Cheng



**Sean Cheng| (+1) 346-473-1515| sc159@rice.edu**

Master student of Computer Science at Rice University  (2021-present).

Master and Bachelor's degree of ECE at Chongqing University, China (2014-2021).

&nbsp;

## 1. [Neural Network Projects](https://github.com/SeanCheng1996/Nerual-network-projects)

### 1.1 [Identify multimodal hate speech using hateful memes dataset(in progress)](https://ai.facebook.com/blog/hateful-memes-challenge-and-data-set/)



### 1.2 [Pets Pawpularity prediction (in progress)](https://www.kaggle.com/c/petfinder-pawpularity-score/data)




### 1.3 [Classify a movie with its poster and description using BERT, CNN and FiLM](https://github.com/SeanCheng1996/Nerual-network-projects/blob/main/Movie%20Classification(CNN%2C%20BERT%2C%20FiLM).ipynb)

It's a class project during Rice university.

In this project, I classify a movie with the poster (image) and plot (text) separately and then apply FiLM ([**Feature-wise Linear Modulation**]( https://arxiv.org/pdf/1709.07871.pdf)) to combine these two types of feature together.



As a result, I got a really good score on training dataset which implies FiLM can help fit the data though it needs careful regularization.

Below is a brief summary of FiLM results:

The breif summary of the above models:

| LearningRate | Regularization(weight-decay) | overfit | train_acc | test_acc |
| ------------ | ---------------------------- | ------- | --------- | -------- |
| 1e-4         | None                         | Yes     | 0.859     | 0.741    |
| 1e-5         | None                         | Yes     | **0.969** | 0.754    |
| 1e-6         | 0.01                         | No      | 0.840     | 0.745    |
| 2e-6         | 0.01                         | No      | 0.880     | 0.744    |
| 2e-7         | 0.001                        | No      | 0.820     | 0.740    |
| 1e-5         | 0.05                         | Yes     | 0.820     | 0.842    |



### 1.4 [Generating text using LSTM and CLIP-based Classification](https://github.com/SeanCheng1996/Nerual-network-projects/blob/main/Text%20Generation%20and%20Image%20Captions(LSTM%2BCLIP).ipynb)

It's a class project during Rice University.

In this project, I generate text without limitation using LSTM with **[Multi30k Dataset](https://github.com/multi30k/dataset)** and then generate captions for a group of images with CNN+LSTM. Finally, I apply [CLIP-based(Contrastive Language-Image Pretraining)](https://openai.com/blog/clip/) Classification on the same database with both images and texts and got a 0.91 test accuracy.





&nbsp;


## 2. Machine Learning Scripts

These are notes on classical machine learning algorithms, based on COMP 540 at Rice University and  **Murphy**'s book, **Probabilistic Machine Learning**.

### 2.1 [Linear Regression.pdf](https://github.com/SeanCheng1996/ML_scripts/blob/main/1.%20Linear%20Regression.pdf)

Including math formula, Probabilistic interpretation, MAP and Ridge regression.

### 2.2 [Linear classification.pdf](https://github.com/SeanCheng1996/ML_scripts/blob/main/2_Linear%20classification.pdf)

Really breif, just intution, more details are in the 3rd notes.

### 2.3 [Gaussian Discriminant Analysis.pdf](https://github.com/SeanCheng1996/ML_scripts/blob/main/3.%20Gaussian%20Discriminant%20Alanysis.pdf)

It contains the mathematical details about Gaussian Discriminant Analysis, including derivative deduction details.

### 2.4 [Kernel.pdf](https://github.com/SeanCheng1996/ML_scripts/blob/main/4.%20Kernel%20and%20SVM.pdf)

From the intuition of kernel trick to kernel method and kernelize linear regression.

### 2.5 [SVM(sparse kernel).pdf](https://github.com/SeanCheng1996/ML_scripts/blob/main/5.%20SVM(sparse%20kernel).pdf)

Support vector machine intuition and details.



&nbsp;

## 3. Publications

#### 3.1 [A Chaotic-Based Routing Optimization Approach for Vehicle Oriented Service in VANET (2021 ITSC)](https://ieeexplore.ieee.org/document/9564935)


#### 3.2 [A Vehicular Service-Oriented Dynamical Routing Searching Algorithm in Software-Defined BusNet (2020 Mobile Information Systems)](https://www.hindawi.com/journals/misy/2020/8856130/)


#### 3.3 [Vehicle Message Distribution Mechanism Based on Improved K-means Adaptive Clustering Algorithm (2020 ITSC)](https://ieeexplore.ieee.org/abstract/document/9294593 )

