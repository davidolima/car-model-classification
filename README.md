# Car Model Classification using Keras
## About
This repository was created for a deep learning course which took place at the Federal University of Bahia (UFBA) and was lectured by Prof. Luciano Rebouças. 
For it's final project we were asked to create and train two different models of our choosing over the [Stanford Cars Dataset](https://www.kaggle.com/datasets/jessicali9530/stanford-cars-dataset).

These are the models I chose:
 - VGG19
 - ResNet50V2

We were instructed to train these models and evaluate their performance through the construction of graphs and using the k-fold cross-validation method.

## My Results
Although the results weren't the greatest, considering the limited time alocated for this project, I see it as a good result. All models were trained on 50 epochs and using 3-fold cross-validation, more information can be found in the [main notebook](https://github.com/davidolima/car-model-classification/blob/main/main.ipynb).

| Model | Loss | Accuracy | Recall | Precision | F1-Score | mAP |
|  ---  |  --- |    ---   |   ---  |    ---    |    ---   | --- |
| VGG-19 | 3.970 |  0.292   | 0.206  |   0.494   |  0.289   | 0.405 |
| ResNet50V2 | 62.588 |  0.386   | 0.386  |   0.387   |  0.386   | 0.495 |
