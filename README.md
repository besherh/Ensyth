# EnSyth
This page contains the latest version of EnSyth: A Pruning Approach to Synthesis of Deep Learning Ensembles

* [**Latest (2019) Conference Version**](https://ieeexplore.ieee.org/document/8913944)
* [**Latest (2019) Paper Preprint**](https://arxiv.org/abs/1907.09286)




# Abstract
Deep neural networks have achieved state-of-art performance in many domains including computer vision, natural language processing and self-driving cars. However, they are very computationally expensive and memory intensive which raises significant challenges when it comes to deploy or train them on strict latency applications or resource-limited environments. As a result, many attempts have been introduced to accelerate and compress deep learning models, however the majority were not able to maintain the same accuracy of the baseline models. In this paper, we describe EnSyth, a deep learning ensemble approach to enhance the predictability of compact neural network’s models. First, we generate a set of diverse compressed deep learning models using different hyperparameters for a pruning method, after that we utilise ensemble learning to synthesise the outputs of the compressed models to compose a new pool of classifiers. Finally, we apply backward elimination on the generated pool to explore the best performing combinations of models. On CIFAR-10, CIFAR-5 data-sets with LeNet-5, EnSyth outperforms the predictability of the baseline model.
