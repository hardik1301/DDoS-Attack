# DDoS-Attack
DDOS attack stands for Distributed Denial of Service, and it is one of the most common ways of DOS (Denial of Service) attack. In DOS attack multiple queries are sent from one host to the destination IP address to crash the server where as in DDOS attack there are multiple hosts that attack on the same server and flood it with multiple queries to crash it down.

This Project basically shows the effect of increasing the number of hidden layers towards accuracy of a model.Increasing the number of hidden layers much more than the sufficient number of layers will cause accuracy in the test set to decrease, yes. It will cause your network to overfit to the training set, that is, it will learn the training data, but it won't be able to generalize to new unseen data.
A linearly separable dataset will need no hidden layers. A nonliner dataset may need one or more hidden layers. It depends on how complicated dataset you are using to train your ANN. 

In this project we have used 3 hidden layers with 50 neurons each and 20 epochs to train our data. This have been selected keeping in mind both parameters - for better accuracy and simplicity of the model.
The model efficiently seperates both attack(out=1) and non-attack(out=0) classes with an accuracy of 88.948%. 


