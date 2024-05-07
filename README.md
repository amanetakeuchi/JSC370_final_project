## JSC370 Final Project: Analysing Author Sentiment of Large Language Model using XGBoost

### Introduction
With the recent remarkable development in Natural Language Processing (NLP), much attention is paid to Large Language Models (LLM), such as ChatGPT by OpenAI, Llama by Meta, and LaMDA by Google. These pre-trained LLMs are capable of many NLP tasks, including question answering, machine translation, text classification, and various other tasks. Having these models achieve State-of-the-Art performance in various NLP tasks, there has been a debate on the ethical issues regarding LLMs. One of the ethical issues mentioned in “Ethical and social risks from Language Model” by Weidinger et al. is social stereotypes and unfair discrimination with the text generated by LLMs. Language models with discriminatory texts and stereotypes can cause different types of harm when utilized in real-world applications. One of the potential harms it could cause is allocational harm, which “may occur when LMs are used in applications that are used to make decisions that affect persons.” (Weidinger, 2021) In order to investigate how biased recently developed LLMs are, this project aims to find the tone of LLMs' opinions when they are prompted to generate opinions on certain topics. In particular, for this project, we will develop a machine-learning model to classify the sentiment of a given text and use the model to classify the sentiment generated by LLMs. 

### Dataset

- The dataset was acquired from this website: https://stonybrooknlp.github.io/PerSenT/
- The preprocessed dataset used for data exploration and model development can be found here: https://github.com/amanetakeuchi/JSC370_final_project/blob/main/author_sentiment_unique.csv

### Data Exploration and Visualization
The link to the website: https://amanetakeuchi.github.io/JSC370_final_project/

### Report 
Link to report: https://github.com/amanetakeuchi/JSC370_final_project/blob/main/JSC370_Final_Project_Report.pdf