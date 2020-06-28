# Movie Genre Predictor
I have create a model that predicts the genre of a movie based on its plot.

## Table of Contents
* [General info](#general-info)
* [Technologies](#technologies)
* [Setup](#setup)
* [Future developments](#future-developments)

## General info
This model was trained using this dataset of [movie plots](https://www.kaggle.com/jrobischon/wikipedia-movie-plots),
using stopwords from [here](https://www.kaggle.com/abbrivia/names-from-35k-wikipedia-movie-plots) and [here](https://www.kaggle.com/rtatman/stopword-lists-for-19-languages).

## Technologies
The project is created with:
* Python version: 3.6.8
* NLTK version: 3.5
* Keras version: 2.3.1
* pandas version: 1.0.3
* numpy version: 1.18.4
* scipy version: 1.4.1
* matplotlib version: 3.2.1
* seaborn version: 0.10.1
and various other libraries included in the requirements.txt file.

## Setup
To run this project, install it locally and run install the packages as required by the requirements.txt file:

```
$ pip install -r requirements.txt
```

To train the model, run all the cells.
To make a prediction, in a new cell, enter
```
categorise(<movie_plot>)
```
The likelihood of each genre will be printed with the genres that have a higher than 50% likelihood of being correct returned as a list.

## Future Developments
Currently, this model can only classify 4 different genres. In the future, I would like to be able to classify more genres with higher accuracy.
