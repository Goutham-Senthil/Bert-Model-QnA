# Question Answering Using BERT

## Overview

This project implements a question answering model using the BERT (Bidirectional Encoder Representations from Transformers) architecture. The model is trained on the Stanford Question Answering Dataset (SQuAD) and is capable of understanding and answering questions based on a given context.

## Dataset

The dataset used for training and evaluation is the Stanford Question Answering Dataset (SQuAD), which is available at [SQuAD2.0:The Stanford Question Answering Dataset](https://rajpurkar.github.io/SQuAD-explorer/)


## Model

The model is based on BERT, a transformer-based model developed by Google. BERT is pre-trained on a large corpus of text and fine-tuned on the SQuAD dataset for the specific task of question answering.

## Installation

To run this project, you need to have Python installed along with the required libraries. The `requirements.txt` file includes all necessary dependencies.

### Create and activate a virtual environment

```bash
python -m venv venv
source venv/bin/activate  # On Windows use `venv\Scripts\activate`
```

### Install dependencies

```bash
pip install -r requirements.txt
```

## Usage

1. Clone this repository.
2. Navigate to the project directory.
3. Ensure you have the dataset in the correct format. 
4. Run the Jupyter Notebook NLP_Project_BERT_Model.ipynb to train and evaluate the model.

## Project Structure

* `NLP_Project_BERT_Model.ipynb`: The Jupyter Notebook containing the model code, training, and evaluation process.
* `requirements.txt`: The file containing all the dependencies needed to run the project.

## Results

The model achieves competitive performance on the SQuAD dataset, providing accurate answers to a wide range of questions based on the given context.


## Contributing

Contributions are welcome! Please feel free to submit a Pull Request.


