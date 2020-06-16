# ML Taxonomy Checkpoint


```python
import numpy as np
import sklearn.linear_model as lm
```

### 1. What is the difference between regression and classification?


```python

```

### 2. What is the difference between supervised and unsupervised learning?


```python

```

### Error-Based Learning with Linear Regression

Suppose I am using leaf size (independent variable) to build a linear regression model of tree height (dependent variable), after noticing a negative correlation between the two quantities.

I first try a model of:

height = $-5\times$ leaf_width $+ 4000$.

I take this model over to three new data points, interested in calculating the error of my model. The three new data points are:
- a pine tree with a height of 6000 cm and leaf width of 10cm;
- a maple tree with a height of 2000 cm and leaf width of 20cm; and
- a palm tree with a height of 900 cm and leaf width of 200cm.

### 3. Calculate my sum of squared errors on these three data points.


```python

```

### Minimizing Error

### 4. Use the variables defined below to build a linear regression with `LinearRegression()`.


```python
X = np.array([10, 20, 200]).reshape(-1, 1)
y = np.array([6000, 2000, 900])
```


```python

```


```python
print(model.coef_)
print(model.intercept_)
```

### 5. What is this (optimal) model's sum of squared errors?


```python

```


```python

```
