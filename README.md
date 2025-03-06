# PyTorch-IMDB-Review-Sentiment-Analysis

# Project Overview

This project implements a sentiment analysis model using PyTorch and LSTM (Long Short-Term Memory) networks. The model is trained on the IMDB movie review dataset, classifying reviews as positive or negative.

# Project Structure

<img width="573" alt="Screenshot 2025-03-06 at 5 29 26 AM" src="https://github.com/user-attachments/assets/ba54c6c5-f20f-4658-b999-8c00dd648c7b" />

# Installation & Setup

1️⃣ Clone the Repository

<img width="495" alt="Screenshot 2025-03-06 at 5 29 44 AM" src="https://github.com/user-attachments/assets/918ad388-fdfc-4f43-9c4e-a1d1b4ea06ca" />

2️⃣ Create Virtual Environment & Install Dependencies

<img width="433" alt="Screenshot 2025-03-06 at 5 30 33 AM" src="https://github.com/user-attachments/assets/24feaa67-b520-490d-a4eb-235e6968e7d4" />

3️⃣ Download & Extract the IMDB Dataset

Ensure that the IMDB dataset (aclImdb_v1.tar.gz) is extracted inside the project folder.
<img width="375" alt="Screenshot 2025-03-06 at 5 30 46 AM" src="https://github.com/user-attachments/assets/e70d6a1d-0826-4d11-8d78-89ef22e7d699" />

🚀 Training the Model

Run the training script to train the LSTM model:
<img width="376" alt="Screenshot 2025-03-06 at 5 30 56 AM" src="https://github.com/user-attachments/assets/b98054cf-6e5f-46d4-bf50-4a141da04ea6" />

This will train the model and save the trained weights as sentiment_lstm.pth.

# Testing the Model

Run the test script to classify new movie reviews:

<img width="436" alt="Screenshot 2025-03-06 at 5 31 05 AM" src="https://github.com/user-attachments/assets/0d0f5f84-5170-4b6b-8a2d-2d51f2cb3d70" />


Example usage:
<img width="568" alt="Screenshot 2025-03-06 at 5 31 15 AM" src="https://github.com/user-attachments/assets/a9ba9dc6-7a0a-4dfc-98a1-805173ea3b7a" />

# Model Architecture

Embedding Layer: Converts words into dense vector representations.

LSTM Layer: Captures sequential patterns in text.

Fully Connected Layer: Outputs a single value (sigmoid activation) for classification.

# Results & Accuracy

The model is trained for 5 epochs with batch size = 32.

Evaluation Metrics: Accuracy, Loss.

Current Test Accuracy:
<img width="280" alt="Screenshot 2025-03-06 at 5 28 07 AM" src="https://github.com/user-attachments/assets/f856c9a0-9cfc-4453-94ec-b68a1e355152" />

👥 Team Members
Chittresh Mitra
Rutvik Rajesh
Anay Sharma
Aniketh Upadhya

