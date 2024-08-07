In this project, I fine-tuned a transformer model for the task of summarization. The goal was to generate concise summaries of given articles or documents. Summarization can be performed in two main ways:

1.Extractive Summarization: This method selected the most important sentences directly from the article to create a summary, ensuring that the summary consisted of exact sentences from the source.
2.Abstractive Summarization: This method generated new sentences that encapsulated the core ideas of the article, producing a summary that included sentences not found in the original text.

I focused on abstractive summarization.
To achieve this, I used Weights and Biases (WandB), a powerful tool for experiment tracking, hyperparameter optimization, and artifact management. WandB integrated easily with various deep learning and machine learning frameworks, making it an ideal choice for managing our project.
