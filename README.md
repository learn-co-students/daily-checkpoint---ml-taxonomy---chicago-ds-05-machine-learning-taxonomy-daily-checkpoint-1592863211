# ML Taxonomy Checkpoint


```python
#run this cell as-is

import numpy as np
import sklearn.linear_model as lm
```

#### 1. What is the difference between regression and classification?


```python
# Write your answer here
```

#### 2. What is the difference between supervised and unsupervised learning?


```python
# Write your answer here
```

## Error-Based Learning with Linear Regression

Suppose I am using leaf size (independent variable) to build a linear regression model of tree height (dependent variable), after noticing a negative correlation between the two quantities.

I first try a model of:

height = $-5 \times$ leaf_width + $4000$.

I'm interested in calculating the error of my model on three new data points I gathered.

The three new data points are:
- a pine tree with a height of 6000 cm and leaf width of 10cm;
- a maple tree with a height of 2000 cm and leaf width of 20cm; and
- a palm tree with a height of 900 cm and leaf width of 200cm.

#### 3. Calculate the sum of squared errors on these three data points.

Ideally, you wouldn't just calculate the arithmetic for these three points, but would write code that dynamically calculates the SSE for this model for any number of data points 


```python
#your work here
```

### Minimizing Error

#### 4. Use the `X` and `y` variables defined below to build a linear regression with `LinearRegression()`.

Print out the coefficient and the intercept for the model you built


```python
X = np.array([10, 20, 200]).reshape(-1, 1)
y = np.array([6000, 2000, 900])
```


```python
# Your work here
```

#### 5. What is this new model's sum of squared errors for the three new points?  

#### How does it compare to the prev. model's SSE for those points?


```python
# Your work here
```


```python

```
