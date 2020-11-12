# Здесь лежат файлы .ipynb с решением заданий на разные темы: машинное обучение, аналитика, теория вероятностей, генеративные алгоритмы, методы Монте-Карло.
Here I describe some projects on machine learning and adjacent fields of study

Опишу несколько проектов по машинному обучению
# Word2Vec.ipynb
The problem is to learn to predict whether a movie review is positive or negative basing on IMDB reviews dataset. Text preprocessing and lemmatization are in the notebook. Text embeddings are made with Word2Vec and SVM is used for learning classification. F-1 score equals 0.895. 
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
