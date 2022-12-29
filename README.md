# Image Classification

Description :

This project classifies images into different classes.

Dataset :

 Bird Species:
 
 1. Dataset contained images of different birds (400 classes) divided into three folders - train(58388), valid(2000), test(2000). Using tensorflow  224x224 sized    images were loaded having 3 channels-RGB.
 
 Fruits and Vegetables:
 
 2.  Dataset contained images of different fruits and vegetables (36 classes) divided into three folders - train(3551), validation(351), test(359). Using tensorflow  224x224 sized images were loaded having 3 channels-RGB.

Languages and libraries:

This project uses python3, tensorflow, keras, numpy, pandas, matplotlib in kaggle jupyter notebook environment.

Models used :

1. Pre-trained EfficientNetB0 model was used for the bird species dataset.
2. A custom covnet having 346K parameters was used for the fruits and vegetables dataset.
