```markdown
# Fake News Detection using Neural Networks

## Project Overview
This project implements a Feedforward Neural Network to classify news headlines as either **Real** or **Fake**. Using Natural Language Processing (NLP) techniques, the model learns to identify patterns and linguistic cues common in misinformation.

## Dataset
The model was trained on a labeled dataset of news headlines:

- **Label 0:** Real News  
- **Label 1:** Fake News  

**Pre-processing:** TF-IDF Vectorization (5,000 features) to convert raw text into numerical input.

## Model Architecture
I designed a Sequential Neural Network with the following structure:

- **Input Layer:** 5,000 features (TF-IDF)  
- **Hidden Layer 1:** 128 neurons with ReLU activation  
- **Hidden Layer 2:** 64 neurons with ReLU activation  
- **Output Layer:** 1 neuron with Sigmoid activation (for binary probability)  

## Hyperparameters
- **Optimizer:** Adam  
- **Loss Function:** Binary Crossentropy  
- **Learning Rate:** 0.001  
- **Epochs:** 10 and 5  

## Results
- **Training Accuracy:** 99%  
- **Validation Accuracy:** 77%  
```
