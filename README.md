# Vietnamese-Poetry-Generation
# Poem Generation with Transformers

This project focuses on generating Vietnamese poems using a Transformer-based model. The model is trained on a dataset of poems and can generate new verses given a starting phrase.

## Purpose
The goal of the project is to build a sequence-to-sequence model that can generate coherent and creative poems in Vietnamese by leveraging the Transformer architecture.

## Features

- **Dataset Preprocessing**: Tokenizes the poem dataset, builds a vocabulary, and encodes the text for training.
- **Transformer Model**: Utilizes multi-headed self-attention layers for generating sequential text (poems).
- **Poem Generation**: Employs a temperature-based sampling method to generate new poems by controlling the randomness of the predictions.
- **Training and Evaluation**: Trains the model using cross-entropy loss and teacher forcing, and generates poems by predicting tokens sequentially.

## Sections

1. **Dataset Preprocessing**: 
   - Tokenizes and prepares the poem data for training.
2. **Model Definition**: 
   - Builds a Transformer-based sequence-to-sequence model in PyTorch.
3. **Training Loop**: 
   - Implements the training logic, including the use of teacher forcing and loss calculation.
4. **Poem Generation**: 
   - Generates poems based on input text using sampling with a temperature parameter to adjust creativity.
5. **Evaluation**: 
   - Outputs generated poems and evaluates the quality of generation.
