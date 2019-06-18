# Deep Learning Fundamentals

This section is intended to introduce you to the essential ideas of deep learning. Hopefully at the end of this section, you have mastered all these topics. A brief list of items in this section are:

- [Artificial Neural Networks](#artificial-neural-networks)
- Deep Neural Networks
- Convolutional Neural Networks
- Reccurent Neural Networks
- Generative Adversarial Networks
- How to Train Networks
- Transfer Learning
- Autoencoders
- implementation of named networks in Keras, and then Tensorflow.

#### Disclaimer:

This is truly a complicated a field. Especially if you don't have a PhD in Mathematics (as I don't), some sections of this tutorial will feel very foreign to you, it might get exhausting and at times you will walk up to the mirror and call yourself stupid, very loudly, multiple times (I DID NOT DO THIS! AT ALL!), but it is also a truly rewarding one. ~~There are some ideas truly fundamental to the field that you should more or less master, **over time**, but for now it is acceptable to just skim over. An example of this would be the backpropagation algorithm (or known as backprop in the hood), in the beginning you won't need to understand it fully, but it will give you a ....~~


### Artificial Neural Networks:

I have seen many tutorials (as I was too lazy to stick to a good one and just go ahead with it), and as a result of that I saw a lot of different ways of explaining this topic. I will try to use the best of all of them here. 

First, we will look at the structure of a neural network. Then we will see how we can evaluate how good our network is doing, and the correlation between **our cost function** and **the accuracy of our model**. Following, we conclude that if we **optimize** the cost function so it has it's lowest value, then our model is at it's best form. 

If you understand the above paragraph, you understand what a neural network is supposed to do, even if you don't know how it is doing so. So let's start with explaining that, to give you a general idea of the basics.
