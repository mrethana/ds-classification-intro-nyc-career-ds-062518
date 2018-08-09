
# Classification   
Thus far we have looked at regression and investigating how we can predict a continuous variable. Another category of problems in data science is to classify class membership. For example, we might want to predict whether or not someone has cancer, whether a video is appropriate for children, or what species an animal is. These problems are fundamentally different in their formulation because of the desired outputs.
  
The simplest case of this is a binary classification of 0 or 1. Typically 0 stands for 'not a member' while 1 stands for 'is a member'.  

Here's some of the most important classification algorithms which we'll investigate in further depth in coming lessons:  

* Logistic Regression
    * Calculates the probability of class membership using the sigmoid function. Then assigns class membmership.
* Decision Trees
    * Split the dataset feature by feature according to which feature will improve the accuracy of classification. For example, those with cholosterol higher than a certain value (to be specified using the tree algorithm) have risk for heart disease, those below that value don't incur a risk. Next, you can go onto another feature in the data set, such as age. 
* Random Forests
    * An ensemble method for combining multiple decision trees.
* Support Vector Machines
    * Draws a decision plane seperating the classes. Maximizes the distance between datapoints and this plane.

# Regression or Classification?
For each of the following scenarios determine whether you would apply a regression or classification algorithm.

### Determining a child's future height.


```python
#Regression
```

### Determining a child's future career.


```python
#Classification
```

### Determining a car's brand.


```python
#Classification
```

### Determining a car's year.


```python
#Regression*
#This one's a little bit tricky.....could potentially be either...but most likely regression would still be appropriate
```

### Determining a car's mileage.


```python
#Regression
```

### Determining a flower's color.


```python
#Classification
```

### Determining a flower's species.


```python
#Classification
```
