Introduction to Machine Learning 

Machine learning is about extracting knowledge from the data. It can be defined as; “Machine learning is a subfield of artificial intelligence, which enables machines to learn from past data or experiences without being explicitly programmed.” As it is evident from the name, it gives the computer that makes it more similar to humans: The ability to learn.
If you want your program to predict, for example, traffic patterns at a busy intersection (task T), you can run it through a machine learning algorithm with data about past traffic patterns (experience E) and, if it has successfully “learned”, it will then do better at predicting future traffic patterns (performance measure P). 
The highly complex nature of many real-world problems, though, often means that inventing specialized algorithms that will solve them perfectly every time is impractical, if not impossible.

Concepts of Learning

Supervised
The computer is presented with example inputs and their desired outputs, given by a “teacher”, and the goal is to learn a general function that maps inputs to outputs. The training process continues until the model achieves the desired level of accuracy on the training data. Some real-life examples are:
    •	Image Classification: You train with images/labels. Then in the future you give a new image expecting that the computer will recognize the new object.
    •	Market Prediction/Regression: You train the computer with historical market data and ask the computer to predict the new price in the future.

Unsupervised
In unsupervised learning the agent learns patterns in the input without any explicit feedback. No labels are given to the learning algorithm, leaving it on its own to find structure in its input. It is used for clustering population in different groups. Unsupervised learning can be a goal in itself (discovering hidden patterns in data).
    •	Clustering: You ask the computer to separate similar data into clusters, this is essential in research and science.
    •	High Dimension Visualization: Use the computer to help us visualize high dimension data.
    •	Generative Models: After a model captures the probability distribution of your input data, it will be able to generate more data. This can be very useful to make your classifier more robust.

Semi-supervised learning
Problems where you have a large amount of input data and only some of the data is labeled, are called semi-supervised learning problems. These problems sit in between both supervised and unsupervised learning. For example, a photo archive where only some of the images are labeled, (e.g. dog, cat, person) and the majority are unlabeled.

Reinforcement Learning 
In this method, a computer program interacts with a dynamic environment in which it must perform a certain goal (such as driving a vehicle or playing a game against an opponent). The program is provided feedback in terms of rewards and punishments as it navigates its problem space. This method aims at using observations from the interaction with the environment to take actions that would maximize the reward or minimize the risk. Reinforcement learning algorithm (called the agent) continuously learns from the environment in an iterative fashion. In the process, the agent learns from its experiences of the environment until it explores the full range of possible states.
In order to produce intelligent programs (also called agents), reinforcement learning goes through the following steps:
    •	Input state is observed by the agent.
    •	Decision making function is used to make the agent perform an action.
    •	After the action is performed, the agent receives reward or reinforcement from the environment.
    •	The state-action pair information about the reward is stored.

Statistical-based Learning: Naive Bayes Model 
Naive Bayes Model is a classification technique based on Bayes' Theorem with an assumption of independence among predictors. In simple terms, a Naive Bayes classifier assumes that the presence of a particular feature in a class is unrelated to the presence of any other feature.
For example, a fruit may be considered to be an apple if it is red, round, and about 3 inches in diameter. Even if these features depend on each other or upon the existence of the other features, all of these properties independently contribute to the probability that this fruit is an apple and that is why it is known as ‘Naive’.
Naive Bayes classifier calculates the probability of an event in the following steps:
    ●	Step 1: Calculate the prior probability for given class labels
    ●	Step 2: Find Likelihood probability with each attribute for each class
    ●	Step 3: Put these value in Bayes Formula and calculate posterior probability.
    ●	Step 4: See which class has a higher probability, given the input belongs to the higher probability class.



Learning by Genetic Algorithms
Operators in Genetic Algorithm: Selection, Mutation, Crossover, Fitness Function

Genetic Algorithm Learning with Neural Networks: 
1 Introduction
2 Biological Neural Networks Vs. Artificial Neural Networks (ANN)
3 Mathematical Model of ANN
4 Activation Functions: Linear. Step Sigmoid
5 Types of ANN: Feed-forward, Recurrent, Single Layered, Multi-Layered
6 Application of Artificial Neural Networks
7 Learning by Training ANN: Supervised vs. Unsupervised Learning. Hebbian Learning, Perceptron Learning. Back - propagation Learning 
