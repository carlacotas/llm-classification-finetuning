# kaggle 'Competitions': LLM Classification Finetuning
# _Finetune LLMs to Predict Human Preference using Chatbot Arena conversations_

This project contains a solution for the [LLM Classification Finetuning](https://www.kaggle.com/competitions/llm-classification-finetuning) competition on Kaggle

**Main objective:** Predict which responses users will prefer in a head-to-head battle between chatbots powered by large language models(LLMs).

**Steps of the data science process:**
1. Understand the original data
2. Data Cleaning
3. Data Exploration
4. Feature Engineering
5. Model Selection and Training
6. Model Evaluation
7. Submission File

**Data**

- train.csv
id - A unique identifier for the row.
model_a/b - The identity of model_a/b. Included in train.csv but not test.csv.
prompt - The prompt that was given as an input (to both models).
response_a/b - The response from model_a/b to the given prompt.
winner_model_a/b/tie - Binary columns marking the judge's selection. The ground truth target column.

- test.csv
id
prompt
response_a/b

- sample_submission.csv A submission file in the correct format.
id
winner_model_a/b/tie - This is what is predicted from the test set.
add Codeadd Markdown


## What's in this project?

`README.md`: That's this file, where you can describe your project and how you built it.

<p/>
  
`llm-classification-finetuning.ipynb`: That's python notebook with the code submitted to the competition.

<p/>


