# Oral-disease
oral diseases analysis
This repository accompanies the publication

....

There are 7 independent directories:

**1- Description of Train_Test_KaggleDS:**
Classification of a dataset named KaggleDS from kaggle:  https://www.kaggle.com/datasets/salmansajid05/oral-diseases
  - without data augmentation
  - normalise all image pixel values to the range [0, 1]
  - resize all images to dimensions 112x112x3 for speeding up the training
  - use stratified k-fold cross validation (with k = 5) to split KaggleDS
  - use the following deep neural network models for training, testing and comparing their performance:
    - ResNet18, ResNet50, ConvNeXt, EfficientNetB0, Transformers (i.e., ViT)
  - use categorical cross entropy as the loss function and f1_score as evaluation metric
  - Models are trained using KaggleDS dataset and the validation is performed using KaggleDS dataset

**2- Description of Train_Test_GoogleDS:**
Classification of a dataset named GoogleDS from Google
  - without data augmentation
  - normalise all image pixel values to the range [0, 1]
  - resize all images to dimensions 112x112x3 for speeding up the training
  - use stratified k-fold cross validation (with k = 5) to split GoogleDS
  - use the following deep neural network models for training, testing and comparing their performance:
    - ResNet18, ResNet50, ConvNeXt, EfficientNetB0, Transformers (i.e., ViT)
  - use categorical cross entropy as the loss function and f1_score as evaluation metric
  - Models are trained using GoogleDS dataset and the validation is performed using GoogleDS dataset

**3- Description of Train_KaggleDS_Test_GoogleDS:**
Classification of a dataset named ds_A from kaggle:  https://www.kaggle.com/datasets/salmansajid05/oral-diseases
  - without data augmentation
  - normalise all image pixel values to the range [0, 1]
  - resize all images to dimensions 112x112x3 for speeding up the training
  - use stratified k-fold cross validation (with k = 5) to split ds_A
  - use the following deep neural network models for training, testing and comparing their performance:
    - ResNet18, ResNet50, ConvNeXt, EfficientNetB0, Transformers (i.e., ViT)
  - use categorical cross entropy as the loss function and f1_score as evaluation metric
  - The best model is trained using KaggleDS dataset and the validation is performed using GoogleDS dataset

**4- Description of Train_GoogleDS_Test_KaggleDS:**
Classification of a dataset named ds_A from kaggle:  https://www.kaggle.com/datasets/salmansajid05/oral-diseases
  - without data augmentation
  - normalise all image pixel values to the range [0, 1]
  - resize all images to dimensions 112x112x3 for speeding up the training
  - use stratified k-fold cross validation (with k = 5) to split ds_A
  - use the following deep neural network models for training, testing and comparing their performance:
    - ResNet18, ResNet50, ConvNeXt, EfficientNetB0, Transformers (i.e., ViT)
  - use categorical cross entropy as the loss function and f1_score as evaluation metric
  - The best model is trained using GoogleDS dataset and the validation is performed using KaggleDS dataset

**5- Description of Train_KaggleDS_GoogleDS_Test_KaggleDS:**
Classification of a dataset named ds_A from kaggle:  https://www.kaggle.com/datasets/salmansajid05/oral-diseases
  - without data augmentation
  - normalise all image pixel values to the range [0, 1]
  - resize all images to dimensions 112x112x3 for speeding up the training
  - use stratified k-fold cross validation (with k = 5) to split ds_A
  - use the following deep neural network models for training, testing and comparing their performance:
    - ResNet18, ResNet50, ConvNeXt, EfficientNetB0, Transformers (i.e., ViT)
  - use categorical cross entropy as the loss function and f1_score as evaluation metric
  - The best model is trained using KaggleDS and GoogleDS datasets and the validation is performed using KaggleDS dataset

**6- Description of Train_KaggleDS_GoogleDS_Test_GoogleDS:**
Classification of a dataset named ds_A from kaggle:  https://www.kaggle.com/datasets/salmansajid05/oral-diseases
  - without data augmentation
  - normalise all image pixel values to the range [0, 1]
  - resize all images to dimensions 112x112x3 for speeding up the training
  - use stratified k-fold cross validation (with k = 5) to split ds_A
  - use the following deep neural network models for training, testing and comparing their performance:
    - ResNet18, ResNet50, ConvNeXt, EfficientNetB0, Transformers (i.e., ViT)
  - use categorical cross entropy as the loss function and f1_score as evaluation metric
  - The best model is trained using KaggleDS and GoogleDS datasets and the validation is performed using GoogleDS dataset

**7- Description of Train_KaggleDS_GoogleDS_Test_KaggleDS_GoogleDS:**
Classification of a dataset named ds_A from kaggle:  https://www.kaggle.com/datasets/salmansajid05/oral-diseases
  - without data augmentation
  - normalise all image pixel values to the range [0, 1]
  - resize all images to dimensions 112x112x3 for speeding up the training
  - use stratified k-fold cross validation (with k = 5) to split ds_A
  - use the following deep neural network models for training, testing and comparing their performance:
    - ResNet18, ResNet50, ConvNeXt, EfficientNetB0, Transformers (i.e., ViT)
  - use categorical cross entropy as the loss function and f1_score as evaluation metric
  - The best model is trained using KaggleDS and GoogleDS datasets and the validation is performed using KaggleDS and GoogleDS datasets
  - The best model is trained on both datasets (using the 5-folds that have been already splitted each, and mixed these folds as follows;
    - KaggleDS dataset: fold1 A1, fold2 B1, fold3 C1, fold4 D1, fold5 E1  
    - GoogleDS dataset: fold1 A2, fold2 B2, fold3 C2, fold4 D2, fold5 E2  
    - Both datasets combined: fold1 with A1 and A2, fold 2 with B1 and B2, fold3 with C1 and C2, fold 4 with D1 and D2, fold5 with E1 and E2)



