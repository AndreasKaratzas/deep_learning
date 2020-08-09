# Multi - Layer Perceptron Neural Network using Pytorch

### Movie Recommendation System implemented using Pytorch in Python

![Genetic Algorithms](https://scx2.b-cdn.net/gfx/news/hires/2018/neuralnetwork.jpg)

In this project, the [MovieLens](https://grouplens.org/datasets/movielens/100k/) dataset was used to classify movies and recommend the best option per user. The repo is organised as follows:
* `dataset_preparation.ipynb`: Jupyter notebook that does data preprocessing
* `matrix_factorization.ipynb`: Jupyter notebook that uses the embeddings technique provided by Pytorch framework to factorize the tabular matrix created by the data preprocessing notebook
* `mlp.ipynb`: Jupyter notebook where the multi - layer perceptron is implemented
* `u.data`: The dataset used in the project

In this project, there was an experiment where matrix factorization was both carried out by a multi - layer perceptron and an embeddings neural network. The result was much better using the embeddings neural network. Finally, there is a Jupyter cell where a custom keras - like neural network fitting was implemented. This cell displays live progress of the neural network while it's training.
