# Oral-disease
oral diseases analysis
This repository accompanies the publication

....

There are 7 independent directories:

1- Description of Train_Test_KaggleDS:
Classification of a dataset named KaggleDS from kaggle:  https://www.kaggle.com/datasets/salmansajid05/oral-diseases
  - without data augmentation
  - normalise all image pixel values to the range [0, 1]
  - resize all images to dimensions 112x112x3 for speeding up the training
  - use stratified k-fold cross validation (with k = 5) to split KaggleDS
  - use the following deep neural network models for training, testing and comparing their performance:
    - ResNet18, ResNet50, ConvNeXt, EfficientNetB0, Transformers (i.e., ViT)
  - use categorical cross entropy as the loss function and f1_score as evaluation metric

2- Description of Train_Test_GoogleDS:
Classification of a dataset named GoogleDS from Google
  - without data augmentation
  - normalise all image pixel values to the range [0, 1]
  - resize all images to dimensions 112x112x3 for speeding up the training
  - use stratified k-fold cross validation (with k = 5) to split GoogleDS
  - use the following deep neural network models for training, testing and comparing their performance:
    - ResNet18, ResNet50, ConvNeXt, EfficientNetB0, Transformers (i.e., ViT)
  - use categorical cross entropy as the loss function and f1_score as evaluation metric

3- Description of Train_KaggleDS_Test_GoogleDS:
Classification of a dataset named ds_A from kaggle:  https://www.kaggle.com/datasets/salmansajid05/oral-diseases
  - without data augmentation
  - normalise all image pixel values to the range [0, 1]
  - resize all images to dimensions 112x112x3 for speeding up the training
  - use stratified k-fold cross validation (with k = 5) to split ds_A
  - use the following deep neural network models for training, testing and comparing their performance:
    - ResNet18, ResNet50, ConvNeXt, EfficientNetB0, Transformers (i.e., ViT)
  - use categorical cross entropy as the loss function and f1_score as evaluation metric

4- Description of Train_GoogleDS_Test_KaggleDS:
Classification of a dataset named ds_A from kaggle:  https://www.kaggle.com/datasets/salmansajid05/oral-diseases
  - without data augmentation
  - normalise all image pixel values to the range [0, 1]
  - resize all images to dimensions 112x112x3 for speeding up the training
  - use stratified k-fold cross validation (with k = 5) to split ds_A
  - use the following deep neural network models for training, testing and comparing their performance:
    - ResNet18, ResNet50, ConvNeXt, EfficientNetB0, Transformers (i.e., ViT)
  - use categorical cross entropy as the loss function and f1_score as evaluation metric

5- Description of Train_KaggleDS_GoogleDS_Test_KaggleDS:
Classification of a dataset named ds_A from kaggle:  https://www.kaggle.com/datasets/salmansajid05/oral-diseases
  - without data augmentation
  - normalise all image pixel values to the range [0, 1]
  - resize all images to dimensions 112x112x3 for speeding up the training
  - use stratified k-fold cross validation (with k = 5) to split ds_A
  - use the following deep neural network models for training, testing and comparing their performance:
    - ResNet18, ResNet50, ConvNeXt, EfficientNetB0, Transformers (i.e., ViT)
  - use categorical cross entropy as the loss function and f1_score as evaluation metric

6- Description of Train_KaggleDS_GoogleDS_Test_GoogleDS:
Classification of a dataset named ds_A from kaggle:  https://www.kaggle.com/datasets/salmansajid05/oral-diseases
  - without data augmentation
  - normalise all image pixel values to the range [0, 1]
  - resize all images to dimensions 112x112x3 for speeding up the training
  - use stratified k-fold cross validation (with k = 5) to split ds_A
  - use the following deep neural network models for training, testing and comparing their performance:
    - ResNet18, ResNet50, ConvNeXt, EfficientNetB0, Transformers (i.e., ViT)
  - use categorical cross entropy as the loss function and f1_score as evaluation metric

7- Description of Train_KaggleDS_GoogleDS_Test_KaggleDS_GoogleDS:
Classification of a dataset named ds_A from kaggle:  https://www.kaggle.com/datasets/salmansajid05/oral-diseases
  - without data augmentation
  - normalise all image pixel values to the range [0, 1]
  - resize all images to dimensions 112x112x3 for speeding up the training
  - use stratified k-fold cross validation (with k = 5) to split ds_A
  - use the following deep neural network models for training, testing and comparing their performance:
    - ResNet18, ResNet50, ConvNeXt, EfficientNetB0, Transformers (i.e., ViT)
  - use categorical cross entropy as the loss function and f1_score as evaluation metric


