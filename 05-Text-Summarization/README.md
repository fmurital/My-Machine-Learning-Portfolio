# News Article Summarization Using Seq2Seq Neural Networks

## Overview

This project explores automatic text summarization using a Sequence-to-Sequence (Seq2Seq) deep learning architecture. The goal was to generate concise summaries of news articles while preserving the key information and overall meaning of the original text.

## Objective

Develop an end-to-end neural network capable of transforming lengthy news articles into shorter, meaningful summaries.

## Methods

### Data Preparation
- Collected and processed news article datasets
- Cleaned and tokenized text data
- Created input-output pairs consisting of articles and corresponding summaries

### Sequence-to-Sequence Architecture
- Implemented an Encoder-Decoder framework
- Utilized Long Short-Term Memory (LSTM) networks
- Learned contextual representations from source articles
- Generated summaries one word at a time through the decoder network

### Model Training
- Converted text into numerical sequences
- Applied padding and tokenization techniques
- Trained the neural network using supervised learning

### Evaluation
- Evaluated generated summaries using BLEU scores
- Compared model-generated summaries with reference summaries
- Assessed the model's ability to retain important information from source articles

## Technologies Used

- Python
- TensorFlow
- Keras
- Natural Language Processing
- LSTM Networks
- Seq2Seq Models

## Skills Demonstrated

- Deep Learning
- Natural Language Processing
- Text Summarization
- Sequence Modeling
- Encoder-Decoder Architectures
- Model Evaluation

## Key Achievement

Built a complete end-to-end text summarization pipeline capable of generating automated summaries for news articles using a Seq2Seq LSTM architecture.

## Challenges

Text summarization is a difficult NLP task because the model must understand context, identify important information, and generate coherent summaries. Limited training data and computational resources impacted overall summarization quality, but the project successfully demonstrated the complete Seq2Seq workflow.

## Learning Outcomes

Through this project, I gained hands-on experience with:

- Encoder-Decoder architectures
- LSTM-based sequence modeling
- Text preprocessing for NLP
- Tokenization and vocabulary management
- BLEU score evaluation
- Deep learning workflows for language generation

## Files

- [/Text_summarizer_Seq_to_seq.ipynb/](https://github.com/fmurital/My-Machine-Learning-Portfolio/blob/main/05-Text-Summarization/Text_summarizer_Seq_to_seq.ipynb) – Complete project notebook 

## Author

Faruk Muritala
