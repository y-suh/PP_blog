---
layout: single
classes: wide 

title: "What is Machine Learning"



header:
  teaser: /assets/images/future.jpg
  overlay_image: /assets/images/future.jpg
excerpt: "Computers are able to see, hear and learn. Welcome to the Future."

permalink: /computer-vision/what-is-machine-learning/

path: ""

---

<br/>

<figure style="width: 600px" class="align-center">
  <img src="{{ site.url }}{{ site.baseurl }}/assets/images/ML1.png" alt="">
  <figcaption>Machine learning applications for optimizing material designs.</figcaption>
</figure> 


Machine learning, artificial neural networks, and deep learning are being incorporated into multiple research fields quite dramatically, but what does "**machine learning**" in particular mean? We'll discuss what the term machine learning is in this post and how these techniques are currently being used to study heat transfer.
{: style="text-align: justify;"}

<br/>

# Definition

Machine learning is a subset of **artificial intelligence (AI)** that gives computers the ability to learn without explicit human intervention. Essentially, machine learning involves computers learning by observing provided datasets in order to carry out specific tasks.

A more modern definition by Tom Mitchell would be: "A computer program is said to learn from experience **E** with respect to some class of tasks **T** and performance measure **P**, if its performance at tasks in **T**, as measured by **P**, improves with experience **E**."
{: style="text-align: justify;"}

Machine learning algorithms make decisions by finding patterns and features within massive pools of data, which can easily become overwhelming for researches to harness; we are literally living in a world of too much data. So, what type of algorithms are used in machine learning? In machine learning, algorithms are largely categorized as **Supervised Learning**, **Unsupervised Learning**, and **Reinforcement Learning**. We will put emphasis on supervised learning in this page as it is greatly related to many of the research we do here.
{: style="text-align: justify;"}



<br/>

# Machine Learning Algorithms

## Supervised Learning

In supervised learning, the machine trains on datasets that have labels, or "answers." In other words, we already have a decent understanding of the relationship between the input and output and therefore know what our correct output should be.

<figure style="width: 900px" class="align-center">
  <img src="{{ site.url }}{{ site.baseurl }}/assets/images/supervised.png" alt="">
  <figcaption>Example of a classification problem for predicting heat flux. If the dataset were labelled with the heat transfer (W) of the boiling image, a classifier would learn how to assign heat transfer labels (i.g., 40 W, 60 W, 80 W, 85 W) to the image. A regression model would learn how to predict continuous values of the heat transfer (i.g., 42 W, 55.5 W, etc.)  </figcaption>
</figure> 
Supervised learning problems can be divided into "**classification**" and "**regression**" problems. In a classification problem, the machine learns how to assign a class label to examples from the problem domain. For example, let's say we have boiling bubble images and another image set of  condensation droplets. A classification prediction model would learn how to take any image as in input and predict whether the image have *bubbles* or *droplets* in the image. Another example could be training a model to classify different *types* of bubbles (perhaps bubbles close to CHF had a different shape or characteristic which we would be able to distinguish from other bubbles). In a regression problem, we try to predict results with a continuous output, meaning that we are trying to map input variables to some continuous function. A typical example of a regression problem would be to predict  real-time boiling heat flux based on certain features. As a sample boils, the bubble characteristics change with respect to heat flux, which makes them a suitable candidate to use as features. In our recent work, we demonstrate the real-time prediction of boiling heat flux by using automatically extracted image features. We will learn about this a little more in [this]({{ site.url }}{{ site.baseurl }}/Machine-Learning/what-is-machine-learning/) post. 
{: style="text-align: justify;"}



***The important thing about supervised learning models is that we must have a clear idea of what is the correct answer is. The machine learns what we teach it.***

## Unsupervised Learning

In unsupervised learning, we tackle problems with little or no idea what our results should look like. That is, the data has no labels. The machine finds patterns and features by clustering data based on relationships among the variables in the data. A great advantage of unsupervised learning is that we can find patterns even amidst the noisiest datasets. Unfortunately, it is very difficult to be sure if the pattern is actually meaningful as the process in which the machine made its prediction is less obvious.

## Reinforcement Learning

Lastly, reinforcement is a powerful learning algorithm that learns from trial and error to perform its task. The model is rewarded or penalized depending on whether the decision it made was better or worse for reaching its objective goal. For those of you that are familiar with AlphaGo, it is fun to know that reinforcement learning is the basis for it. 











