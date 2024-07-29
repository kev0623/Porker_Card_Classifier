# Porker_Card_Classifier

The Poker Card Classifier is a deep learning model built using **PyTorch** and the **timm** library. This model is designed to classify images of poker cards into their respective categories. The model uses a pre-trained **EfficientNet-B0** as its base for feature extraction and includes a custom classifier for the final classification.

## Features
**Pre-trained Model**: Utilizes EfficientNet-B0 for feature extraction.

**Custom Classifier**: A fully connected layer for classification into 53 classes (52 cards + 1 for joker or an additional category).

**Training and Evaluation**: Scripts for training the model, evaluating accuracy on validation and test sets.
