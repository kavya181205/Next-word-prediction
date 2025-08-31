# LSTM-based Text Generation Model

This project implements a text generation model using **LSTM (Long Short-Term Memory)** networks with TensorFlow/Keras. The model is trained on textual data to predict the next word in a sequence, enabling the generation of human-like text.

## Features
- Preprocessed text data with **tokenization, sequence padding, and one-hot encoding**.
- Built a deep learning architecture using **Embedding, LSTM, and Dense layers**.
- Trained the model to predict the next word in a sequence.
- Implemented **checkpointing and hyperparameter tuning** to improve accuracy.

## Tech Stack
- **Python**
- **TensorFlow / Keras**
- **NumPy**
- **NLTK / Text Preprocessing**

## Project Workflow
1. Load and clean the dataset (remove punctuation, lowercase text).
2. Tokenize and convert text into sequences.
3. Apply padding and prepare training data (X, y).
4. Build and train the LSTM model.
5. Evaluate model performance and generate new text samples.

## Example Output
Input: "to be or not".
Prediction: "to be or not to"
