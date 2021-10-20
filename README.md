# NYCU-Taipei

This is the GitHub repository of **iGEM team NYCU-Taipei**. It contains all the materials in our software project, which consists of the crawler, the dataset, the selected features, and our model implementations.


## Project Description

The project of NYCU-Taipei is about Nattokinase. However, the cleavage sites of Nattokinase remain unelucidated currently. The main goal of this software project is to predict the cleavage sites of Nattokinase. The past research for protease-substrate relationship is highly related to its folding structures. However, learning the features of the folding structures is computationally expensive. 

Since Nattokinase is one of the S8-family protease, we exploit the S8-family database to analyze the prediction. Our model has great performances on predicting S8-family protease-substrate relationships and also significantly mitigating the computational cost. In addition, it provides the potential cleavage sites of Nattokinase that are worth experimenting and verifying. Last but not least, anyone can reach our codes and application to predict the cleavage sites of the S8 family protease. Our project not only is an efficient model but also analyzes the protease-substrate relationship precisely.


## Building Models

There are two kinds of model, which is SVM and neural network (NN), respectively. The implementation are both contained in our repository.

If you want to execute our original codes, please clone our repository to your device or open these codes with google colab. You can run the codes ```NN.ipynb``` for neural network model and ```SVM.ipynb``` for SVM model.

## Application

In addition, we provide a user-friendly application. You can run ```S8_family_Protease_Subtrate_Relation_Prediction_APP.ipynb```, then input the protease data and protein sequence, our model will predict the cleavage site in that specific protein. The output format will be the content and position of the found cleavage sites.

You can access our application by the [link](https://colab.research.google.com/github/mmi366127/NYCU-Taipei/blob/main/S8_family_Protease_Subtrate_Relation_Prediction_APP.ipynb). 

#### Enjoy predicting your cleavages site!

