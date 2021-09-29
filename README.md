# Hack Technology / Project Attempted


## What you built? 

I attempted to build an artificial neural network (ANN) to predict Combined Cycle Power Plant output based on various features. The ANN has two hidden layers that aid with developing the regression model.

The first image  below details the data used, including parameters like temperature, ambient pressure, relative humidity, and exhaust vaccuum to predict energy output (PE). 

The second image shows the training process over the course of 100 epochs, with loss decreasing with each iteration.

[ANN Data](anndata.PNG)

[ANN Training](anntrain.PNG)

## Who Did What?

I followed the tutorial to use the data to predict energy output with high accuracy, building the model by adding input, output, and hidden layers.

## What you learned

The ANN worked well and predicted test set energy output with high accuracy. However, I learned that performance improves with diminishing returns as we train the model more and more with increasing numbers of epochs. The epoch specifies how many times we traverse our dataset during training. 

It was difficult to improve performance past 100 epochs, so it seemed difficult to improve accuracy once it was already high.

## Authors

Anand Mittal

## Acknowledgments

https://www.udemy.com/course/linear-regression-with-artificial-neural-network/