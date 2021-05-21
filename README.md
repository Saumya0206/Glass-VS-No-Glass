# Glass-VS-No-Glass
<br/>
This repositary contains the Major Project for Pattern Recognition and Machine Learning Course

# Problem Statement
Face recognition is a fascinating application in the field of image recognition. However face images with glasses create hindrance .The goal of this project is to classify images of people into two classes: Glass and No-Glass based upon whether they wear a glass in the image or not. However, there is a variety in the shape, design and appearance of glasses which makes it challenging. The glass vs. no glass recognition can help in applications like face-recognition based biometric systems, detection of suspicious faces through security cameras, etc.

# Description

We have a dataset generated using Generative Adversarial Neural Network (GAN) which consists of feature vectors of images of people wearing or not wearing glasses. The GAN network creates these images using a 512 number latent vector. We use various classification algorithms and compare their results in this report.. Apart from the GAN dataset , another image dataset was used to implement CNN for classification.
There are three code files - one for gan and two for image dataset

# Description of datasets

GAN dataset contains 4500  rows where each row represents a train-image with 514 columns containing :
- 1 id column
- 1 glasses column : Class label - 0 for no glass and 1 for glass
- 512 latent vector columns
The image dataset has 2779 glass and 2151 no glass data samples.

# Sources of datasets
- [GAN Feature vector](https://www.kaggle.com/jeffheaton/glasses-or-no-glasses/)
- [Image dataset](https://www.kaggle.com/jorgebuenoperez/datacleaningglassesnoglasses)

# Models used 
- For GAN :
   - Random Forest Classification
   - KNN
   - Logistic Regression
   - SVM
   - MLP
   - Gaussian Naive Bayes<br/>
    We also make use of  PCA and LDA for dimensionality reduction and feature selection.
    
- For image dataset
    - CNN
    - VGG

# Project Report 
[Report](https://drive.google.com/file/d/1FbDRtUySr2OP6fmL1rNJFu1g3M5l-TrI/view?usp=sharing)
