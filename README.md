# neural-nets
My learning path on neural nets and deeplearning

###lecture 1:

####Input Data: The raw information you feed into the network.

####Weights and Biases: Parameters the network adjusts during training to make accurate predictions.

####Forward Pass: This is where the input data is transformed layer by layer through weighted sums and activation functions, culminating in an output.

####Loss Function: This metric quantifies how far off your network's predictions are from the actual targets. The goal is to minimize this loss.

####Backpropagation: This is the technique used to calculate the gradient of the loss function with respect to each parameter in the network. By following these gradients, we know how to adjust the parameters to reduce the loss.

####Gradient Descent: This iterative optimization process uses the gradient information to minimize the loss function. It's like following a trail of breadcrumbs to the lowest point in a valley.

####Parameter Scaling: Small networks might have a handful of parameters, but modern neural networks can have billions or even trillions. Regardless of size, they operate on the same principles: forward pass, loss calculation, backpropagation, and parameter updates.

####Complexity and Emergence: As networks grow, they exhibit fascinating emergent properties, especially when tackling complex tasks. Take GPT models, for instance: trained on vast amounts of text, they predict the next word in a sequence. This task, powered by a colossal number of parameters and data, reveals surprising capabilities.

####Optimization Techniques: While the basics remain the same, advanced techniques like stochastic gradient descent and different loss functions, such as cross-entropy loss, are used to fine-tune performance.
