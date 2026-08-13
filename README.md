# Sentiment Classification with Neural Language Models

This repository contains my Stage 1 submission for Assignment 2.

The project uses a GRU-based neural network to classify movie reviews as:

- 0 = negative
- 1 = positive

## Files

- `stage1_notebook.ipynb` - model development, training, and evaluation
- `public_test_predictions.csv` - predictions for the public test set
- `model_checkpoint/` - saved trained model checkpoint
- `requirements.txt` - required Python packages

## Model

The model uses the following structure:

Embedding → GRU → Dropout → Linear Classification Layer

## Installation

Install the required packages with:

```bash
pip install -r requirements.txt
```

## Running

Open `stage1_notebook.ipynb` and run the notebook cells in order.

The notebook trains the model using `train.csv`, evaluates the saved model on `public_test.csv`, and generates `public_test_predictions.csv`.