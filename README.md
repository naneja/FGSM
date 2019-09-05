# ADVERSARIAL EXAMPLE GENERATION

## Fast Gradient Sign Attack
Source: https://pytorch.org/tutorials/beginner/fgsm_tutorial.html

Fast Gradient Sign Attack (FGSM) described by Goodfellow et. al. in Explaining and Harnessing Adversarial Examples is designed to attack neural networks by leveraging the way they learn, gradients. 

The idea is simple, rather than working to minimize the loss by adjusting the weights based on the backpropagated gradients, the attack adjusts the input data to maximize the loss based on the same backpropagated gradients.

In other words, the attack uses the gradient of the loss w.r.t the input data, then adjusts the input data to maximize the loss.

* [MNIST-PySGD.ipynb](https://github.com/naneja/FGSM/blob/master/n-FGSM.ipynb) implements FGSM.

## Feedback
Please submit your feedback to [Nagender Aneja](http://expert.ubd.edu.bn/nagender.aneja). Please write an email (naneja@gmail.com) 

## Project Members
*  [Dr. Nagender Aneja](http://expert.ubd.edu.bn/nagender.aneja), nagender.aneja@ubd.edu.bn
*  [Dr. Sandhya Aneja](http://expert.ubd.edu.bn/sandhya.aneja), sandhya.aneja@ubd.edu.bn

