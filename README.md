# Transformer network: Question answering
We explore an application of the transformer architecture, question answering.

Question answering (QA) is a task of natural language processing that aims to automatically answer questions. The goal of extractive QA is to identify the portion of the text that contains the answer to a question. For example, when tasked with answering the question 'When will Jane go to Africa?' given the text data 'Jane visits Africa in September', the question answering model will highlight 'September'.

- We will fine-tune a pre-trained transformer model to a custom dataset to answer questions about stories.
- We will implement an extractive QA model in TensorFlow and in PyTorch.

I did this project in the [Sequence Models](https://www.coursera.org/learn/nlp-sequence-models) course as part of the [Deep Learning Specialization](https://www.coursera.org/specializations/deep-learning).

## Dataset
We use the [QA bAbI dataset](https://research.fb.com/downloads/babi/), which is one of the bAbI datasets generated by [Facebook AI Research](https://ai.facebook.com/) to advance natural language processing.
