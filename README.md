# Fooling Convolutional Neural Networks

This jupyter notebook explores various techniques that can be used to fool image classifiers. We use the VGG-16 network, which will predict what an object in an image is from 1000 possible classes.
The aim of this work is to modify an image of a coffee mug, such that to a human it is still recognisable, but the network will mis-classify the image.

This piece of work was produced for a class assignment.

## Techniques

These are the different approaches we explore to get the netowrk to mis-classify:

* Multiple blurring techniques
* Warping
* Changing brightness
* Modifying colour
* Removing distinctive features
* Changing backgrounds and environments
* Different picture angles
* Drawings

These are two recently published pieces of research we examine which can fool a convolutional neural network:

* [Jiawei Su, Danilo Vasconcellos Vargas, Sakurai Kouichi, One pixel attack] (https://arxiv.org/abs/1710.08864)
* [Tom B. Brown, Dandelion Mané, Aurko Roy, Martín Abadi, Justin Gilmer, Adversarial Patch] (https://arxiv.org/abs/1712.09665)

