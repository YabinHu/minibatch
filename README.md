# MiniBatch

Mini-batching is a technique for training a neural network on subsets of the dataset instead of all the data at one time. This provides the ability to train a model, even if a computer lacks the memory to store the entire dataset.

Mini-batching is computationally inefficient, since you can't calculate the loss function output value of your model simultaneously across all samples. However, this is a small price to pay in order to be able to run the model at all.

This project is a simple implementation of Mini-batching for study purpose. It is a part of lesson 8 of Self Driving Car Nano Degree on Udacity.

## License
MiniBatch is a free software and may be redistributed under the terms specified in the
[LICENSE](/LICENSE) file.
