# Spotting Economy News: Deep Neural Network Model

## Objective
While exploring the interaction between Recurrent Neural Network layers and sequential data from big chunks of text, the US Economy News dataset seemed a great one to train a model from. The main objective of this project is to create a machine learning model that can automatically classify a given piece of text as either an economical news article or a non-economical news article with a high degree of accuracy. This classification is achieved by training the model on a labeled dataset, where each instance of text is pre-identified relevant or non-relevant. The model learns to recognize patterns and features tied to high context keywords, enabling it to generalize and make accurate predictions on unseen data.

## Applications
This capability is crucial for applications such as content filtering, media analysis, and information retrieval, where distinguishing between journalistic content and other types of text is necessary. By automating this process, the model aims to assist in efficiently managing and categorizing large volumes of textual data, enhancing the effectiveness of digital content management systems, and providing valuable insights into the nature and distribution of information across various media platforms.

## Result
### Custom Text Import And Prediction
After recognizing the right methodologies towards text preprocessing, vectorization, and padding, a function allows the feed of any custom text, and analyze the relevance of words based off its classification of an "economical news article" or "non-economical news article". Results overall give the correct prediction as unseen pieces of news article texts are fed into the model. However, at the 72% of validation accuracy, the main limitations form this model consists in the limited journals variety and size. Furthermore, the main insight is distinguished as definition of an economical news article is a grey line iself, deducted from the dataset survey and secondary research.


### Contributors:
* Louis Golding
* Jan Macieowski
* Fabian Perez
* Ali Rammal

