# Few-Shot-Learning-using-Prototypical-Network
Simple alternative Implementation of Prototypical Networks for Few Shot Learning (paper, code) in PyTorch.

Prototypical Networks
As shown in the reference paper Prototypical Networks are trained to embed samples features in a vectorial space, in particular, at each episode (iteration), a number of samples for a subset of classes are selected and sent through the model, for each subset of class c a number of samples' features (n_support) are used to guess the prototype (their barycentre coordinates in the vectorial space) for that class, so then the distances between the remaining n_query samples and their class barycentre can be minimized.
