# Explainable-AI-Projects
This repository is a collection of projects demonstrating the application of Explainable AI (XAI) methods on various machine learning tasks. The goal is to provide insights into how "black-box" models make their predictions.

## Projects
- [Cat-Dog Classification](https://xaidataset.github.io/dataset/#cats-and-dogs-classification-(cat&dog-xai)): An image classification model for cats and dogs, with XAI applied to visualize the features influencing the predictions.
- [Face Glass Detection](https://xaidataset.github.io/dataset/#face-glasses-recognition-(glasses-xai)): A computer vision model that detects if a person is wearing glasses. XAI is used to confirm the model is focusing on the correct facial features.
- [Tweet Sentiment Analysis](https://www.kaggle.com/competitions/tweet-sentiment-extraction/data): An NLP project that classifies tweet sentiment(positive, negtive or neutral). XAI is applied to understand which words drive the sentiment predictions.

## XAI Methods
- **LIME**: A technique that explains the predictions of any machine learning model by approximating it locally with an interpretable model.
- **SHAP**: A method that uses game theory to explain the output of any machine learning model. It assigns a value to each feature, indicating its contribution to the prediction.
- **Integrated Gradient**: A technique for attributing a model's prediction to its input features (e.g., pixels in an image). It assigns an importance score to each feature based on the integral of the model's gradient with respect to the input.
- **Grad-CAM**: A technique for visualizing the regions of an image that are most important for a convolutional neural network's (CNN) classification decision. 
- **Occlusion**: A simple and intuitive method for understanding which parts of an image are most important for a model's prediction.

## Getting Started
- Clone the repository: `git clone https://github.com/your-username/Explainable-AI-Projects.git`
- Install requirements: `pip install -r requirements.txt`
- Each project notebook contains instructions for usage.
