# Youtube Dislikes
## About
Dislikes are a good metric for judging the quality of a video before you watch it. With youtube removing dislikes, we want to attempt to predict youtube dislikes from other publically available data on the video. 
1. [Linear_Regression](https://github.com/randomname512/1015_project/blob/main/Linear_Regression.ipynb)
2. [Deep_Learning](https://github.com/randomname512/1015_project/blob/main/Deep_Learning.ipynb)

## Contributers
- Shao Xian - a bit of everything
- Sam Neo - a bit of everything

## Problem
- Predicting dislike count on a youtube video based on other data.
- What kind of techniques are required to predict dislikes.

## Models
- Linear Regression
- Deep Learning

## Conclusion
- View counts have a high linear correlation with dislikes, while comment counts have a low linear correlation with dislikes.
- Basic linear regression is not very effective on complex and varied data with no clearly defined relationship.
- Breaking the data down to individual channels and using that to estabish a baseline seems to help marginally.
- Ultimately the problem can be solved to a certain extent with machine learning taking into account the text data and learning the hidden relationships that we cannot find ourselves.

## What we learnt
- Neural Networks, Keras, Tensorflow
- How to make use of LSTMs(RNN)
- Preprocessing techniques like tokenisation
- Process both numerical and text data
- Youtube API

## References
- [Main Dataset](https://www.kaggle.com/datasets/dmitrynikolaev/youtube-dislikes-dataset?datasetId=1794708)
- [Secondary Dataset](https://www.kaggle.com/datasets/datasnaek/youtube-new)
- [Deep Learning for youtube dislikes](https://pub.towardsai.net/youtube-dislikes-prediction-in-real-time-working-with-a-combination-of-data-a-practical-guide-fb7e88b0b445#cf4c)
