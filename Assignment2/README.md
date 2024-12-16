# Machine Learning Tasks: SMS Classification and Image Generation

This repository contains the implementation of multiple machine learning tasks involving Recurrent Neural Networks (RNNs), Long Short-Term Memory Networks (LSTMs), and Conditional GANs (cGANs).

---

## Task 1: SMS Spam Classification

### Dataset:
- **SMS Spam Collection Dataset**: [Link to dataset](https://www.kaggle.com/datasets/uciml/sms-spam-collection-dataset)  
- The dataset contains SMS messages labeled as either `spam` or `ham` (not spam).

### Objectives:
1. **Build a Classifier:**
   - Using an RNN model.
   - Using an LSTM model.
2. **Constraints:**
   - Both models should have a similar number of parameters (exactly the same is not necessary).
3. **Comparison:**
   - Evaluate and compare the performance of RNN and LSTM classifiers.
   - Provide example results to highlight the differences in model predictions.

---

## Task 2: SMS Autocomplete

### Objective:
- Create RNN and LSTM models that generate the second half of an SMS message based on the first half.

### Details:
1. Introduce a special `<END>` token for the model to indicate the end of the output sequence.
2. Train both RNN and LSTM models for this task with:
   - Similar number of parameters for a fair comparison.
3. **Comparison:**
   - Evaluate the performance of both models on the autocomplete task.
   - Highlight key differences and provide example outputs.

---

## Task 3: Conditional GAN for Fashion MNIST

### Dataset:
- **Fashion MNIST**: [Link to dataset](https://www.kaggle.com/datasets/zalando-research/fashionmnist)  
- Contains 10 classes of fashion-related images (e.g., T-shirts, dresses, shoes, etc.).

### Objective:
- Build a Conditional GAN (cGAN) to generate fashion images conditioned on their class labels.

### Model Details:
1. **Generator:**
   - Input: Random codeword from the latent space and a label (class).
   - Output: Generated image corresponding to the input label.
2. **Discriminator:**
   - Input: Pairs of (Image, Label).
   - Output: Classify whether the pair is real or fake.

### Evaluation:
- Generate 4 example images for each class (using random latent codewords) to showcase the performance of the model.


