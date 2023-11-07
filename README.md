# Welcome to My Convex Optimization
***

## Task
TODO - What is the problem? And where is the challenge?

## Description
One of the main challenges of Data Science and more specifically in Machine Learning is the performance measure.
How to measure performance efficiently so that our model predictions meet the business objectives?

For example, let's pretend our goal is to classify fruits to know if a fruit is an apple, an orange, or something else, depending on some attributes (color, shape, weight...).

Intuitively, the measure of 'how far' is our model prediction from the correct answer tells us about the effectiveness of our algorithm. The farther is our prediction the worse is our performance. We can then define a cost function based on this 'distance'. We want to minimize this cost function in order to have the best prediction possible, i.e we want to find the point where the value of this cost function is the lowest.

Generally, minimizing a function is not an easy task. However, some functions are easier to optimize than others: Convex functions.

On the left, the function is said to be convex: it is beautifully round. On the contrary, the function on the right has a lot of valleys and bumps.
The minimum of the convex function is much easier to reach: we just need to follow the slope ! With non convex function, following the slope would not work since reaching a cavity does not ensure that this cavity is the lowest one !

Finding the minimum of a convex function is called ... Convex Optimization ! You might have already heard about something called Gradient Descent before. This is an algorithm which does exactly that: following the slope to the cavity.

This project is meant to be an introduction to some convex optimization tools and to implement your own optimization algorithm.

## Installation
TODO - How to install your project? npm install? make? make re?

## Usage
python my_convex_optimization.py
```
x_min: 0.41, f(x_min): 0.29
xmin: 0.41, f(x_min): 0.29
The optimal value is:  -11  and is reached for x =  [3. 4.]
```

### The Core Team


<span><i>Made at <a href='https://qwasar.io'>Qwasar SV -- Software Engineering School</a></i></span>
<span><img alt='Qwasar SV -- Software Engineering School's Logo' src='https://storage.googleapis.com/qwasar-public/qwasar-logo_50x50.png' width='20px'></span>
