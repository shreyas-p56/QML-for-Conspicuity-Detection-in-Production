# Task 3

Consider a more sophisticated model using an interesting real-world dataset (here the MNIST dataset), [**Quanvolutional Neural Networks**](https://pennylane.ai/qml/demos/tutorial_quanvolution/) . Work through the example, Implement and present your steps in a notebook and comment on the important steps.

# Application

Quanvolutional filters each produce a feature map when applied to an input tensor, by transforming spatially-local subsections of the input tensor using the quanvolutional filter.

However unlike the simple element-wise matrix multiplication operation that a classical convolutional filter applies, a
quanvolutional filters transforms input data using a quantum
circuit, which can be structured or random.