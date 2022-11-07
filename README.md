# sigmoid-datathon
This repository contains our approaches on the Emotion Classification Task in the [Sigmoid Data Science Hackathon](https://www.hackerearth.com/challenges/competitive/sigmoid-data-science-hackathon-machine-learning-challenge/)

The focus of sentiment analysis is to derive information from human language for interpreting views and feelings to assign polarities like positive, negative, or neutral. However, emotion detection aims at finding out more specific sentiment tones such as happiness, sadness, depression, anxiety, etc. Emotion detection can be applied to different types of unstructured data with text being one of such types of data.

#Task
Predict emotions from posts, reviews, blogs, or tweets that focus on a product/ service experience. Each query of the test data can have one or all of the emotions tagged to it.

#Dataset description
The dataset contains the following files:
 train.csv: 7724x14
 test.csv: 400x2
 sample_submission.csv: 10x14
 
The columns provided in the dataset are as follows-
![image](column_description.png)
 

# Contributors - [Ramashish Gupta](https://www.linkedin.com/in/ramashish-gupta-697508214/), [Archit Mangrulkar](https://www.linkedin.com/in/archit-mangrulkar-033327199/), [Parv Jain](https://www.linkedin.com/in/parv-jain-5a9a961bb/), [Harsh Khandelwal](https://www.linkedin.com/in/harsh16khandelwal/)

# Sections

# Final Presentation

# Model Architecture
The Transformer Architecture used by us is shown in the figure. We used the pre-trained models released by [HuggingFace](https://huggingface.co/models).\

# Results

We achieved an F1-score of 0.5945 using an ensemble of Roberta models for anger, neutral and other classes

# File descriptions
