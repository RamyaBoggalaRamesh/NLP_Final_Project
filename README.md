Next-Word Prediction Using Pretrained Transformers (GPT-2, GPT-Neo)

Project Overview:

  This project leverages pretrained transformer models, specifically GPT-2 and GPT-Neo, for predicting the next word in a given text input. 
  The goal is to demonstrate the capabilities of these models in generating the next most probable word based on an input text, 
  as well as evaluating model performance using loss and perplexity metrics.

 
Features

  Next-Word Prediction: Predict the next word in a given input text using GPT-2 and GPT-Neo.
  Model Evaluation: Compute the loss and perplexity to assess the model's performance on different datasets.
  Interactive Mode: Allows users to input text and see predictions interactively.
  Top-K Predictions Visualization: Visualizes the top-k predictions for the next word along with their probabilities.

  
Prerequisites

Ensure that you have the following dependencies installed before running the project:
  Python 3.x
  PyTorch (CUDA support recommended for GPU acceleration)
  Transformers library by Hugging Face

  
Necessary Libraries :

  pip install torch transformers matplotlib numpy

  
Project Structure:

Datsets:
Pizza.txt

NLP.txt

Python Source File

Next_Word_Prediction_Using_LLMs

Next you can clone the code from git using

  git clone command
  
Next step is to run the code using google colab- cell by cell and observe the results.


Model Evaluation

  The script evaluates the model on different datasets (pizza.txt, NLP.txt) and computes metrics like loss and perplexity. The results will be displayed, 
  and graphs of the evaluation results will be plotted using Matplotlib.


Visualizing Top-K Predictions:

  The script also generates bar charts showing the top-k predictions for the next word, including their probabilities. This helps in visualizing how confident 
  the model is about its predictions.


Example output:

  Input: "The pizza is very"
  
  Predicted Next Word: "delicious"
  
  Loss: 0.3421
  
  Top-K predictions
  
  Perplexity: 1.41

