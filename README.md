# Projects for the Udacity Machine Learning Nanodegree

During the course of the Nanodegree in Machine Learning there are a variety of projects to complete, and in this repository I showcase those projects. 

Each folder above contains a project, which in turn primarily consists of an IPython notebook. The additional files in the folders are either used for visuals or contain the data used to generate predictions. To view the results of each project it is sufficient to open the IPython notebooks in each of the folders.

Here is a description of each project, largely taken from the [Udacity course website](https://www.udacity.com/course/machine-learning-engineer-nanodegree--nd009).

### Predicting Boston Housing Prices

The Boston housing market is highly competitive. Using a few basic machine learning concepts, I find the best selling price for the home of a client. This is done by using the Boston Housing dataset which contains aggregated data on various features for houses in Greater Boston communities, including the median value of homes for each of those areas. In this project I build an optimal model based on a statistical analysis with the (simple) tools available. I then use this model to estimate the best selling price for the client’s home.

### Finding Donors for CharityML

CharityML is a fictitious charity organization. After nearly 32,000 letters sent to people in the community, CharityML determined that every donation they received came from someone that was making more than $50,000 annually. To expand their potential donor base, CharityML has decided to send letters to residents of California, but to only those most likely to donate to the charity. With nearly 15 million working Californians, I build an algorithm to best identify potential donors and reduce overhead cost of sending mail. In this project I evaluate and optimize several different supervised learners to determine which algorithm provides the highest donation yield while also reducing the total number of letters being sent.

### Creating Customer Segments

A wholesale distributor recently tested a change to their delivery method for some customers, by moving from a morning delivery service five days a week to a cheaper evening delivery service three days a week. Initial testing did not discover any significant unsatisfactory results, so they implemented the cheaper option for all customers. Almost immediately, the distributor began getting complaints about the delivery service change and customers were canceling deliveries - losing the distributor more money than what was being saved. In this project I find what types of customers they have to help them make better, more informed business decisions in the future. To do this I use unsupervised learning techniques to see if any similarities exist between customers, and how to best segment customers into distinct categories.  This involves preprocessing the data and suitably dimensionally reducing it using PCA, whose results are interpreted in a way that would be useful to a marketer.

### Train a Smartcab to Drive

![smartcab](http://personalpages.to.infn.it/~dgalloni/smartcab_small.png)

In the not-so-distant future, taxicab companies across the United States no longer employ human drivers to operate their fleet of vehicles. Instead, the taxicabs are operated by self-driving agents — known as smartcabs — to transport people from one location to another within the cities those companies operate. In major metropolitan areas, such as Chicago, New York City, and San Francisco, an increasing number of people have come to rely on smartcabs to get to where they need to go as safely and efficiently as possible. Although smartcabs have become the transport of choice, concerns arose that a self-driving agent might not be as safe or efficient as human drivers, particularly when considering city traffic lights and other vehicles. To alleviate these concerns, in this project I use reinforcement learning techniques to construct a demonstration of a smartcab operating in real-time to prove that both safety and efficiency can be achieved.

### Image Classification (CIFAR-10) Using Deep Learning

Using Deep Learning written in TensorFlow, I classify images from the CIFAR-10 dataset using a convolutional neural network. An example of such images is seen here:

![cifar10](http://personalpages.to.infn.it/~dgalloni/cifar10_horse.gif)

I evaluate the accuracy of the model on a validation and test set, and with only a simple model obtain 61.8% test-set accuracy.

### Letter identification (notMNIST dataset) Using Deep Learning

Using a relatively simple but well-trained neural network architecture written using TensorFlow, I classify notMNIST images, exemplified here (image taken from [here](http://yaroslavvb.blogspot.it/2011/09/notmnist-dataset.html)):

![notMNIST](http://personalpages.to.infn.it/~dgalloni/notMNIST_small.png)

The convolutional neural network I built is able to classify letters correctly with 96.64% accuracy on the test set. I also include my trained TensorFlow model for loading into the notebook.

## Additional info on the Nanodegree

The [Machine Learning Nanodegree](https://www.udacity.com/course/machine-learning-engineer-nanodegree--nd009) takes on average approximately 500 hours to complete, and is based on lectures and six projects. The purpose of the projects is to consolidate the lecture material and showcase some of the tools learned during the course of the Nanodegree. It is also very useful for getting experience with larger projects on frequent and important use-cases in machine learning.
