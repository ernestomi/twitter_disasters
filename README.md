# Detecting disasters in Twitter

This repository holds my dissertation for the title of MSc in Business Analytics at Imperial College London

* The full text can be found [here](docs/disaster_detection.pdf)
* The accompanying Jupyter Notebooks are available both as rendered HTML and pure IPYNB
* The analysis is split into two:
  * The first, [found here](notebooks/disaster_detection.html), contains the data and feature engineering and the less computationally intensive models. 
  * The second, [found here](notebooks/disaster_detection_bert.html), contains the BERT model that requires a much larger machine to run

## Contact

If you are interested in the work here, and would like some help or advice implementing NLP models get in touch!

## Abstract

Twitter has become an important channel for users to publish data about their experiences, this presents an opportunity for emergency response teams and disaster managers to detect events relevant to them. In this study a series of statistical and neural language models that detect the mention of a disaster in tweets are proposed. The models were trained and tested on a public dataset from Kaggle. The best model was a pre-trained BERT network that achieved a 90.87% F1 score and 88.94% accu- racy, highlighting that current open source technology is able to successfully detect emergency situation in social media. In addition, this study concluded that other less computationally intensive methods such as Support Vector Machines can also achieve decent scores between 79% and 80%. This report was also intended to serve as a guide and review of the literature on the subject of classification tasks on short text data.