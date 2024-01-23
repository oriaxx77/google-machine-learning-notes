# Google Machine Learning Course Notes
* https://developers.google.com/machine-learning/crash-course/ml-intro

Table Of Contents
1. [Introduction](#introduction)
2. [Framing](#framing)
3. [Linear Regression] (#linear-regression)



<a name="introduction"></a>
# 1. Introduction
* Not much here


<a name="framing"></a>
# 2. Framing
* How to frame a task as a machine learning problem
* **(Supervised) Machine Learning**:
  * ML systems learn how to combine inputs to give predictions on never-seen-before-data
* **Label**
  * The variable we are predicting
  * `y` is used to represent it
  * The process is alled labeling or annotating
* **Features**
  * Input variables we are using for the predicting the label
  * `(x1, x2, ... xn)` is use to represent them
* **Example**
  * A particular instance of data **x**
  * **Labeled example**:
    * {features, label}: **(x,y)**
    * Used to train data
  * **Unlabeled example**:
    * {features, label?}: **(x,?)**
    * Used to make predictions on new data
  * **Model** 
    * Map examples to learn new **y'**
* **Training**
  * Creating (learning) the model
* **Inference**
  * Applying the model to unlabeled data
* **Regression**
  * The model predicts continuous values
* **Classification**
  * The model predicts discrete values      

<a name="linear-regression"></a>
# 3. Linear Regression
