# Question Answering using BERT

This repository contains a single Python script `NLP_Project_BERT_Model.ipynb` to fine-tune and use a BERT model for question answering with the SQuAD dataset.

## Requirements  

Install requirements:

pip install -r requirements.txt

## Usage

`NLP_Project_BERT_Model.ipynb` has the following key steps:

1. Load and preprocess SQuAD dataset
2. Fine-tune BERT model with simpletransformers
3. Evaluate fine-tuned model 
4. Make predictions on new examples 

The trained model and configuration are saved to `/models`.

## Dataset source

[SQuAD2.0:The Stanford Question Answering Dataset](https://rajpurkar.github.io/SQuAD-explorer/)


