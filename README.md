# Here are notebooks containing solutions of problems from different topics: Machine Learning (NLP, VAE, Image classification), Analytics, Sampling Algorithms and MCMC
Here I describe some projects

Опишу несколько проектов
# Word2Vec.ipynb
The problem is to learn to predict whether a movie review is positive or negative basing on IMDB reviews dataset. Text preprocessing and lemmatization are in the notebook. Text embeddings are made with Word2Vec and SVM is used for training classification. F-1 score equals 0.895. Comparison with a pre-trained model for wor2vec embeddings showed that in this case it is better to train the embeddings on a given dateset.
TF-IDF gives better score, but Word2Vec allows to learn faster.

На базе датасета комментариев IMDB необходимо научиться предсказывать положительный комментарий или нет. В ноутбуке производится предобработка и лемматизация текстов с дальнейшим применением Word2Vec для векторного представления. Далее для классификации используется метод опорных векторов. Итоговый f1-score на тесте - 0.895.
# VAE_example.ipynb
Variational Autoencoder implementation and demostration of its work on a famous MNIST dataset.

Реализация вариационного автоенкодера с примером работы на известном датасете MNIST.
# CNN_Model.ipynb
A basic example of CNN applied to a image classification problem (historical digit dataset Arkiv Digital Sweden, https://ardisdataset.github.io/ARDIS/).

Базовый пример работы свёрточных нейронных сетей на изображениях из датасета (historical digit dataset Arkiv Digital Sweden, https://ardisdataset.github.io/ARDIS/). Рукописные цифры, но НЕ MNIST.
# LDA_and_Gibbs_Sampling.ipynb
Sampling the most likely words from a topic using Latent Dirichlet Allocation and Gibbs Sampling. Implementations of LDA model and Gibbs sampling are provided in the notebook.
# Metropolis-Hastings algorithm.ipynb
Number of coloured graph vertices approximation via Law of Large Numbers and Metropolis-Hastings algorithm. Implementation of Metropolis-Hastings algorithm is provided in the notebook.
# Sampling_and_Random_partition.ipynb
Implementation of a number of algorithms to sample from a distribution (including Box-Muller algorithm) and estimation of an expected number of subsets in the case of random partition of a set.

