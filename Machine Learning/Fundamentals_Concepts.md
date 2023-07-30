<div align=“center”>
    <h1> Fundamentals Concepts of Machine Learning </h1>
</div>

![](images/machine_learning_cover.jpg)
***

# Introduction
The purpose of this document is to enlist some of the fundamental concepts of machine learning to understand what happens when ML algorithms are being trained and used. 
***
# What is Machine Learning?

Machine learning is a programming field that studies how computers can learn things without explicitly programming them. It brings them the ability to do things that only humans can.

ML is a subset of AI that intends to allow computers to do things like humans. It currently belongs to the narrow AI, which means that computers can learn and perform one task well but can have multiple abilities as humans do. It tries this by finding patterns in a set of data. Then it is deep learning, which is a subfield of ML that uses neural networks to model data. ML overlaps with data science because it is needed to understand the data and how to work with it to train and make use of ML models.


![](images/machine_learning_data_science_diagram.jpg)


Like every technology, ML appears because a business need of using large amounts of data they collect to find patterns that improve the business or solve problems they have.

## Types of Machine Learning

There are two main categories of ML, the first one is called supervised learning which consists essentially in give input of data labeled so the computer can figure out patterns to get that label. The second one is called unsupervised learning, in it the computer has to figure out the groups or categories cause the data isn't labeled. And there is a third one called reinforcement learning in which the computer learns by trial and error.

![](images/types_of_ml.jpg)
***
In a nutshell, ML is about asking the computer to do something without giving instructions on how to do it. It has to figure out by finding patterns in the input data they receive.

# Machine Learning Models Building Framework

Overall ML consists of three main tasks: collecting data, modeling data, and deploying the model. The main focus of building ml algorithms is in modeling, for instance, to deliver practical solutions a [framework](https://www.mrdbourke.com/a-6-step-field-guide-for-building-machine-learning-projects/) is needed to approach different kinds of problems.

![](images/machine_learning_buildin_framework.png)

## 1. Problem definition

**What problem are we trying to solve?**

if you know the steps to solve a particular problem it is better to not use ML. Probably hand-code instructions will work.

The most common ML types are supervised, unsupervised and transfer learning. The main type of supervised ML are classification and regression, the first one refers to predicting if a thing is one or another. The second one refers to predicting a particular value. Transfer learning refers to existing ML models learning new patterns without forgetting the old.

## 2. Data

**What kind of data do we have?**

The main type of data is structured and unstructured. An example of structured data is for example a spreadsheet with columns representing features and rows observations. Unstructured data are things like images or audio. Then there is static and streaming data. Static data is typically in CSV files, which contain lots of data you can use to train ML models. Streaming data is data that changes all the time, you find it when the model is moving to production. 

A typical DS workflow starts with data analysis to find insights, then you create an ML model that aport value to the business.



## 3. Evaluation

**What defines success for us?**

The different metrics in ML exist for evaluating how well the model is predicting, they depend on the type of problem we are solving (classification or regression). It is probably that changes as the project goes on.

## 4. Features

**What do we know about the data?**

Feature refers to variables we're using as input for the model we are going to train. It's just another form of data within structured or unstructured data.

The process of selecting the features for the ML model is called **feature engineering**. There are numerical features, categorical features and derived features.

## 5. Modeling

**Based on our problem and data, what model should we use?**

This step can be broken down into three parts:
* Choosing and training the model
* Tuning a model
* Model comparison

### Splitting the data

We need to split our entire dataset into three datasets: the training set, the validation set and the test set. The first one is used to teach the model, the second one is used to validate the learning of the model, and the third one is used to test if the model can generalize with data it has never seen before.

### Choosing the model

Depending on the problem and the type of data one model works better than others. Since ML is an iterative process it is better to start with a less complex model with a little part of the data instead of all the training data set, this is because the experiments can take longer. You can add complexity and data to your models based on previous results.

### Tuning

ML models have parameters you can change to improve their performance, for example, the number of forests in a random forest algorithm or the number of layers in neural networks. They may differ from one algorithm to another.

### Comparison

**How will our model perform in the real world?**

* Avoid overfitting and underfitting, you want your model to be able to generalize. Overfitting is when it learns the data too well, and underfitting is when it learns the data too poorly.
* Do not use the test set when training the model.
* Always compare different models with the same dataset.
* One best performance metric does not equal the best model.

### Experimentation

**What have we tried/what else can we try?**

ML is an iterative process so always be open to change and try new models, and different approaches and modify data.

# References
+ [TensorFlow Developer Certificate in 2023: Zero to Mastery](https://www.udemy.com/course/tensorflow-developer-certificate-machine-learning-zero-to-mastery/)





