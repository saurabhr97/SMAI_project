# SMAI Project

## Team

#### Team Number: 
17
#### Project: 
Project number: 25 - Text classification using deep character-based Convolutional Neural Networks

#### Members:
* Eashwar Subramanian (201501163)
* Pranav Kamojjhala (201501213)
* Rishabh Arora (201501010)
* Saurabh Ravindranath (201501159)

## Models

* 6-layered CNN as described in the paper https://arxiv.org/abs/1509.01626
* 29-layered CNN as described in the paper https://arxiv.org/abs/1606.01781
* 54-layered CNN similar to the one described in the paper https://arxiv.org/abs/1606.01781

## Datasets

* The Yelp Polarity dataset. Link: https://drive.google.com/open?id=1d0TeJIaEUW3om7Nlp2PrQYZeOswkYWzE
* The DBPedia Ontolody dataset (2014). Link: https://drive.google.com/open?id=15CxfoWJ4K10ypOYdgR4EXXa_Xt1rLb7c

## Requirements

The packages required to run the code are:
* The pytoch package, which can be installed using the instructions from: http://pytorch.org/
* The numpy package

## Usage

The following commands are used to run the codes:

* Training on Yelp Polarity Dataset: python3 yelp_train.py <Model to be used: (cnn6, cnn29, cnn54)> \<path to dataset>
* Testing on Yelp Polarity Dataset: python3 yelp_test.py <Model to be used: (cnn6, cnn29, cnn54)> \<path to dataset> \<path to weights file>
* Training on DBPedia Ontology Dataset: python3 dbpedia_train.py <Model to be used: (cnn6, cnn29, cnn54)> \<path to dataset>
* Testing on DBPedia Ontology Dataset: python3 dbpedia_test.py <Model to be used: (cnn6, cnn29, cnn54)> \<path to dataset> \<path to weights file>

## Trained Models

The list of models we've trained and the links to their weight files are available in the weights.txt file
