# LSTM-Shakespeare-like-Text-Generation
Generating Shakespeare-like text using Recurrent Neural Networks

## Data Set Used
 - https://storage.googleapis.com/download.tensorflow.org/data/shakespeare.txt
 
---

# Overview
- In this project, I use the dataset extracted from Shakespeare's writing.
- The objective is to train an LSTM network to predict the next character in a sequence of characters. 

## RNN's 
- A RNN contains a temporal loop in which the hidden layer not only gives an output but it feeds itself as well.
- An extra dimension is added which is time!
- RNN can recall what happened in the previous time stamp so it works great with sequence of text. 
- Feedforward ANNs are so constrained with their fixed number of input and outputs.
  - For example, a CNN will have fixed size image (28x28) and generates a fixed output (class or probabilities).
- Feedforward ANN have a fixed configuration, i.e.: same number of hidden layers and weights.
- Recurrent Neural Networks offer huge advantage over feedforward ANN and they are much more fun!
- RNN allow us to work with a sequence of vectors: 
    - Sequence in inputs
    - Sequence in outputs
    - Sequence in both!
- LSTM networks are type of RNN that are designed to remember long term dependencies by default.
- LSTM can remember and recall information for a prolonged period of time.

## Notes:
- This code is adopted from TF2.0 Documentation: https://www.tensorflow.org/beta/tutorials/text/text_generation
- Check out this reference: http://karpathy.github.io/2015/05/21/rnn-effectiveness/

---

## Improvements to the model:
The easiest thing you can do to improve the results it to train it for longer.

More ideas:
*   Experiment with a different start string
*   Try adding another RNN layer to improve the model's accuracy
*   Adjust the temperature parameter to generate more or less random predictions



