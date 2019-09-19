# ADVERSARIAL EXAMPLE GENERATION

## Fast Gradient Sign Attack
Source: https://pytorch.org/tutorials/beginner/fgsm_tutorial.html

Fast Gradient Sign Attack (FGSM) described by Goodfellow et. al. in Explaining and Harnessing Adversarial Examples is designed to attack neural networks by leveraging the way they learn, gradients. 

The idea is simple, rather than working to minimize the loss by adjusting the weights based on the backpropagated gradients, the attack adjusts the input data to maximize the loss based on the same backpropagated gradients.

In other words, the attack uses the gradient of the loss w.r.t the input data, then adjusts the input data to maximize the loss.

#### Note: If Python Notebook doesn't render, copy url in https://nbviewer.jupyter.org

* Contact: Nagender Aneja, naneja@gmail.com, http://researchid.co/naneja
