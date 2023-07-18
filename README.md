# Hamrahe Aval FAQ Deep Learning Model

This is a deep learning model that was trained on the Hamrahe Aval FAQ dataset, with pre-defined answers. The model uses a GRU layer to handle the sequential nature of the data, and a classification layer with a number of unique answers for the available questions.

## Dataset

The Hamrahe Aval FAQ dataset contains a collection of frequently asked questions, along with pre-defined answers. The dataset was preprocessed to remove any irrelevant information and to clean up the data. The final dataset contains over 1300 questions and answers.

## Model Architecture

The deep learning model uses a GRU layer to handle the sequential nature of the data. The GRU layer is followed by a classification layer, which is used to predict the answer to a given question. The classification layer has a number of unique answers for the available questions.

## Training

The model was trained on a GPU-enabled machine using the TensorFlow framework. The model was trained using a batch size of 128 and a learning rate of 0.001.

## Evaluation

The model was evaluated on a test set containing 20% of the original dataset. The model achieved an accuracy of 82% on the test set, which indicates that the model is performing well on the given task.
