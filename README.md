# ag_news_keras_cnn
Using 120k news titles and 4 categories from the AG News set, a model is created to predict the news category given a news title.

Utilized Keras to generate a Convolutional Neural Network (CNN) and baseline dense neural network with a 200 dimensional Glove embedding. Predicted news category with a 87% test set accuracy.

### SetUp:
1. Install all packages from the Import statement.
2. The 200 dimensional file of glove.6B.200d.txt can be downloaded at a zip file [here](http://nlp.stanford.edu/data/glove.6B.zip) (822 MB). See main page at the [GloVe: Global Vectors for Word Representation](https://nlp.stanford.edu/projects/glove/) introduction page.
3. Designate the file path of the input data and Gensim embedding file as a string in the 'directory' object.
4. Download data file from the PyTorchNLPBook github [here](https://github.com/joosthub/PyTorchNLPBook/tree/master/data)

### Sources:
1. [Word Embedding use in Keras](https://machinelearningmastery.com/use-word-embedding-layers-deep-learning-keras/)

2. [Original AG News Set](http://www.di.unipi.it/~gulli/AG_corpus_of_news_articles.html)

3. [Convolutional Neural Networks in Keras](https://realpython.com/python-keras-text-classification/#convolutional-neural-networks-cnn)

### Author:
[Aaron Moskowitz](https://www.linkedin.com/in/aaroncmoskowitz/)
