# BCI-EEG-Project
Brain Computer Interface

**EEG Imagined Speech Classification using CNN + BiLSTM**

This project explores Brain-Computer Interface (BCI) technology by classifying imagined speech from EEG signals using a deep learning model (CNN + BiLSTM). The goal is to convert brain signals into meaningful text, enabling communication for individuals with speech or motor impairments.

   ** Source: Kumar’s Imagined Speech EEG Dataset**

    Contents:
        EEG recordings during imagined speech tasks (Characters, Digits, and Images)
        Multiple subjects and sessions
        14 selected EEG channels used for training
    Preprocessing:
        Null row removal
        Normalization
        Filtered and saved to CSV format
🧠 Model Architecture
    Convolutional Neural Network (CNN) for spatial feature extraction
    Bidirectional LSTM (BiLSTM) for temporal sequence learning
    Batch Normalization and Dropout for regularization
    Softmax for final classification
📈 Accuracy

**Achieved 94% validation accuracy on imagined speech EEG classification task.**
🛠 Technologies Used
    Python
    NumPy, Pandas
    TensorFlow / Keras
    Matplotlib
    Jupyter Notebook
📦 File Structure

EEG-BCI-Project/
├── EEG2.ipynb             # Main notebook (training + evaluation)
├── preprocessed_data/     # Cleaned CSV EEG data
├── models/                # (Optional) Saved trained models
├── requirements.txt       # Python dependencies
└── README.md              # This file


    Name: Saicharan
    Education: Pursuing my BE in AIML in Chaitanya Bharathi Institute of Technology,Completed my  Diploma in CSE (GPT Hyd) – 9.71 CGPA
    GitHub: @SaiCharan-N
