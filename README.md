# GradientDescent
In this lab, we'll implement the basic functions of the Gradient Descent algorithm to find the boundary in a small dataset.First, we'll start with some functions that will help us plot and visualize the data.

Implementing the basic functions

Here is your turn to shine. Implement the following formulas, as explained in the text.

Sigmoid activation function
𝜎(𝑥)=11+𝑒−𝑥
 
Output (prediction) formula
𝑦̂ =𝜎(𝑤1𝑥1+𝑤2𝑥2+𝑏)
 
Error function
𝐸𝑟𝑟𝑜𝑟(𝑦,𝑦̂ )=−𝑦log(𝑦̂ )−(1−𝑦)log(1−𝑦̂ )
 
The function that updates the weights
𝑤𝑖⟶𝑤𝑖+𝛼(𝑦−𝑦̂ )𝑥𝑖
 
𝑏⟶𝑏+𝛼(𝑦−𝑦̂ )

This function will help us iterate the gradient descent algorithm through all the data, for a number of epochs. It will also plot the data, and some of the boundary lines obtained as we run the algorithm.

Time to train the algorithm!

When we run the function, we'll obtain the following:

10 updates with the current training loss and accuracy
A plot of the data and some of the boundary lines obtained. The final one is in black. Notice how the lines get closer and closer to the best fit, as we go through more epochs.
A plot of the error function. Notice how it decreases as we go through more epochs.

