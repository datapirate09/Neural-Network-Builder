This repository presents an intuitive and user-friendly Neural Network Builder designed to help users understand and experiment with the inner workings of neural networks without diving deep into complex source code or extensive documentation.
Rather than overwhelming users with dense technical details, this project emphasizes clarity through simplicity. For simplicity a lot of the function names have been drawn from the Tensorflow library and hence the application layer code will largely remain intact.

# Key Features:

**Modular Design:** Each part of the neural network, from layers to optimizers, is modular and easily extendable.

**Forward Propagation:** The forward propgation has been implemented for Dense Networks and also Recurrent Networks

**Backward Propagation:** The backward propagation code snippets have been implemented using the chain rule of calculus for both Dense Networks and Recurrent Neural Networks. The implementation is done in such a way that it highlights the step-by-step derivation of gradient calculations

**Support for Recurrent Neural Networks:** The concept of RNN's is not widely explored from a mathematical point of view. This repo does just that. It implements some of the key concepts of an RNN from mathematical fundamentals.

**Example Implementations:** The implementation of the networks is verified by training and testing the network on a few examples. The accuracy on both the training and validation set can be checked in code.

**Tokenizer:** A basic Tokenizer implementation is also provided for the purpose of several Natural Language Processing based Tasks. It consists of the fit_on_texts and texts_to_sequences and pad_sequences functionalities.
