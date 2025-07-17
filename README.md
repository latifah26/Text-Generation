# Text-Generation using Deep Learning
This project explores the performance of different recurrent neural network architectures for the task of text generation. We compare four models: 

RNN (Recurrent Neural Network)

LSTM (Long Short-Term Memory) 

Bi-LSTM (Bidirectional LSTM)

LSTM with Attention Mechanism

📌 Objective

The goal is to evaluate how well each model can learn and generate coherent text based on a given dataset, considering their ability to capture context, sequence dependencies, and long-term memory.

🔍 Key Features

Preprocessing and tokenization of raw text data

Implementation of each model using Keras/TensorFlow

Training and evaluation of models on the same dataset

Generation of text samples for qualitative comparison

Performance visualization using training loss and accuracy

📊 Models Compared

| Model	                | Strengths                                          |	Limitations
|:----------------------|:--------------------------------------------------:|----------------------------------:|
RNN	                    | Simple and fast                                    | Struggles with long-term memory
|LSTM	                  | Handles long-term dependencies well	               | Slower training
|Bi-LSTM	              | Uses both past and future context	                 | More computationally expensive
|LSTM + Attention	      | Focuses on relevant parts of input sequence	       | Requires more training resources
|:----------------------|:--------------------------------------------------:|----------------------------------:|



📦 Output

Generated text samples from each model

Training and validation loss graphs

Summary of model performance and observations


