# ECG_Heartbeat_Classification_RNN

This project aims to classify heartbeat signals from electrocardiogram (ECG) data into normal and abnormal categories using a deep neural network, specifically a Gated Recurrent Unit (GRU).

## Dataset

The dataset used in this project is the ECG Heartbeat Categorization Dataset, which consists of segmented and preprocessed ECG signals from the MIT-BIH Arrhythmia Dataset and The PTB Diagnostic ECG Database. The dataset contains samples corresponding to normal heartbeats and heartbeats affected by different arrhythmias and myocardial infarction.

## Model Architecture

The model architecture includes a GRU layer to capture temporal dependencies in the ECG signals. The output layer uses the sigmoid activation function for binary classification.

## Usage

1. **Dataset:** Download the ECG Heartbeat Categorization Dataset and update the file path in the code accordingly.

2. **Dependencies:** Install the required Python libraries using the following command:
                     pip install numpy pandas matplotlib tensorflow

   
Training the Model: Execute the provided code in a Jupyter notebook or a Python script to train the model on your dataset.

Evaluation: Evaluate the model's performance on a test set and analyze the results.

Results
Include any key results or metrics achieved by the model on the test set.

License
This project is licensed under the MIT License.

Acknowledgments
Dataset Source: Physionet's MIT-BIH Arrhythmia Dataset and PTB Diagnostic ECG Database
Paper: Mohammad Kachuee, Shayan Fazeli, and Majid Sarrafzadeh. "ECG Heartbeat Classification: A Deep Transferable Representation." arXiv preprint arXiv:1805.00794 (2018).
Contributing
Feel free to contribute to the project by opening issues or submitting pull requests. Your input is valuable!
