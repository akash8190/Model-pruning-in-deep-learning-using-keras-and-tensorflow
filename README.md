# Model-pruning-in-deep-learning-using-keras-and-tensorflow

## About model pruning

![title](https://miro.medium.com/max/1934/1*4dJE_vHfGpPBtXLLXLmnBQ.png)

Pruning is a technique in deep learning that aids in the development of smaller and more efficient neural networks. It's a model optimization technique that involves eliminating unnecessary values in the weight tensor.

Deep Learning models these days require a significant amount of computing, memory, and power which becomes a bottleneck in the conditions where we need real-time inference or to run models on edge devices and browsers with limited computational resources. Energy efficiency is a major concern for current deep learning models. One of the methods for tackling this efficiency is enabling inference efficiency

Larger Model => More Memory References => More Energy

## There are many challenges face  when our model is large


 ## First challenge — Models are getting larger

![title](https://miro.medium.com/max/1050/1*b21KCzVEkc1E_vzV77amQg.png)


## The Second Challenge: Speed

![title](https://miro.medium.com/max/1050/1*6uCSuFU6HdLN8M-vLIm7Qg.png)

## The Third Challenge: Energy Efficiency

AlphaGo: 1920 CPUs and 280 GPUs, $3000 electric bill per game

![title](https://miro.medium.com/max/728/1*Y3xXEtYzFODF3XKNIgTTbA.png)

## so the best solution of all these problem is prunning to reduce cost  or reduce model complexity

## In this repo we simply create a deep learning model and do pruning on them  and see the diffrence before pruning and after pruning and the result says that there is little diffrence in accuracy or loss in our model.

## refrences of creating this repo
Twoards data science blog post
Tenserflow.org documantation


