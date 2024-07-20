# **ChatGPT User Reviews**

## Introduction

ChatGPT is a chatbot and virtual assistant created by OpenAI, released on November 30, 2022. It utilizes large language models, allowing users to guide and shape conversations according to preferred length, format, style, detail, and language.

## Data Description
This dataset comprises daily updates of user reviews and ratings for the ChatGPT Android App. It includes several key attributes that detail various aspects of the reviews, offering insights into user experiences and feedback over time.


# Project Journey
The journey, outlined in the comprehensive table of contents, covered various stages:

1. Importing Packages
2. Load Data
3. Exploratory Data Analysis (EDA)
4. Data Engineering
5. Modeling
6. Model Evaluation
7. Model Deployment
8. Model Deployment
9. Conclusion

MultinomialNB was a strong candidate for classifying user reviews due to its effectiveness with text data, computational efficiency, and suitability for high-dimensional, sparse feature spaces

# Installation
To run this project, ensure you have Python installed. Follow these steps to set up the environment:

1. **Clone the repository:**
"git clone https://github.com/yourusername/ChatGPT-User-Reviews-Analysis.git"
"cd ChatGPT-User-Reviews-Analysis"

2. **Create a virtual environment:**
"python -m venv env"
"source env/bin/activate  # On Windows, use `env\Scripts\activate`"

**Summary and Impact**
So MultinomialNB was a strong candidate for classifying user reviews due to its effectiveness with text data, computational efficiency, and suitability for high-dimensional, sparse feature spaces. It can help in accurately categorizing the sentiment of user reviews, providing valuable insights into user feedback. The overall accuracy of the model is 0.95, meaning the model correctly classifies 95% of the instances. Our model seems to be performing quite well in making predictions on unseen data even though there seems to be a class imbalance. Improvements could be done on our model if there was an equal distribution of the data. In conclusion, majority of users are satsified with their overall experience of using the ChatGPT Android App.