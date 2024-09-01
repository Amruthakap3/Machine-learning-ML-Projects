# Machine Learning work

# Machine Learning Projects Overview

This repository contains several machine learning projects, each focusing on different techniques and applications. Below is a brief overview of each project.

## Table of Contents
- [Project 1: Customer Satisfaction dataset analysis](#project-1-Customer-Satisfaction-dataset-analysis)
- [Project 2: Image Classification with CNNs](#project-2-image-classification-with-cnns)
- [Project 3: Clustering Customer Data](#project-3-clustering-customer-data)
- [Project 4: Reinforcement Learning for Game AI](#project-4-reinforcement-learning-for-game-ai)
- [Project 5: Sentiment Analysis with NLP](#project-5-sentiment-analysis-with-nlp)

## Project 1: Customer Satisfaction dataset analysis
- **Description**: Customer Satisfaction dataset and analyzed the data in multiple ways like plotting, correlation to identify the relationship with the decision variable, etc. We followed the following steps

- **pipelines to impute and prepare data
- **pipelines to perform classification
- **Encode the labels for multi-classification
- **converting decision trees to text and graph
- **performing grid search to optimize a few hyperparameters

- **Outcome**: The obtained results show that the average accuracy measure for all models was around 48% to 55%.
  GridSearchCV was not performed exhaustively although the last two experiments and the plotted graph show that modest improvements can be made by just optimizing a few hyperparameters.


## Project 2: Image Classification with CNNs
- **Description**: Implementation of a Convolutional Neural Network (CNN) to classify images from the CIFAR-10 dataset.
- **Key Techniques**: Convolutional Neural Networks, Data Augmentation.
- **Dataset**: [CIFAR-10](https://www.cs.toronto.edu/~kriz/cifar.html).
- **Outcome**: Achieved an accuracy of 85% on the test set.

## Project 3: Clustering Customer Data
- **Description**: Applied K-means clustering to segment customers based on purchasing behavior.
- **Key Techniques**: K-means Clustering, PCA for dimensionality reduction.
- **Dataset**: Simulated customer purchase data.
- **Outcome**: Identified 3 distinct customer segments.

## Project 4: Reinforcement Learning for Game AI
- **Description**: Developed a reinforcement learning agent to play and win a custom-built game.
- **Key Techniques**: Q-learning, Policy Gradients.
- **Dataset**: Game simulation environment.
- **Outcome**: The agent learned to win 80% of the games after training.

## Project 5: Sentiment Analysis with NLP
- **Description**: Built an NLP model to perform sentiment analysis on movie reviews.
- **Key Techniques**: Natural Language Processing, LSTM, Word Embeddings.
- **Dataset**: [IMDb Movie Reviews Dataset](https://ai.stanford.edu/~amaas/data/sentiment/).
- **Outcome**: The model achieved an F1 score of 0.87 on the test set.

## How to Use This Repository
To explore each project, navigate to the respective directory and follow the instructions provided in the individual README files.

## Contributing
Contributions are welcome! Please fork the repository and submit a pull request.

## License
This repository is licensed under the MIT License. See the [LICENSE](LICENSE) file for more details.

