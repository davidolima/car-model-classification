# Car Model Classification using Keras
## About
This repository was created for a deep learning course which took place at the Federal University of Bahia (UFBA) and was lectured by Prof. Luciano Rebouças. 
For it's final project we were asked to create and train two different models of our choosing over the [Stanford Cars Dataset](https://www.kaggle.com/datasets/jessicali9530/stanford-cars-dataset).

These are the models I chose:
 - VGG19
 - ResNet50V2

We were instructed to train these models and evaluate their performance through the construction of graphs and using the k-fold cross-validation method.

## My Results
### Trained on 50 epochs and using 3-fold cross-validation

| Model | Loss | Accuracy | Recall | Precision | F1-Score | mAP |
|  ---  |  --- |    ---   |   ---  |    ---    |    ---   | --- |
| VGG-19 | 3.778 | 0.284 | 0.177 | 0.495 | 0.259 | 0.402 |
| ResNet50V2 | 62.971 |  0.397   | 0.397  |   0.397   |  0.397   | 0.505 |
