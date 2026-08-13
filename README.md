Sentiment Classification with Neural Language Models

This repository is my Stage 1 submission for Assignment 2.

The project uses models to classify movie reviews as:

- 0 = negative
- 1 = positive

Files

- `stage1_notebook.ipynb` - model development, training, and evaluation
- `public_test_predictions.csv` - predictions for the public test set
- `model_checkpoint/` - saved trained model checkpoint
- `requirements.txt` - required Python packages

Model

The model uses the following structure:

Embedding 
 GRU 
 Dropout 
 Linear Classification Layer


Install the required packages with the following code command:


pip install -r requirements.txt


Running

Opens `stage1_notebook.ipynb` and run the notebook cells in order.

The notebook trains the model using `train.csv`, evaluates the saved model on `public_test.csv`, and generates `public_test_predictions.csv`.