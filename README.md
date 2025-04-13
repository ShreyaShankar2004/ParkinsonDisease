# ParkinsonDisease
A CNN-LSTM Hybrid Model for Parkinson’s Disease Detection from Handwritten Spirals Using Transfer Learning 

Overview
This project focuses on developing deep learning-based models to detect Parkinson's Disease (PD) using handwriting pattern features. We implement and compare different architectures including CNN+LSTM, EfficientNet, and a Custom Hybrid Model to achieve accurate diagnosis results.

Files
cnn_lstm_model.ipynb:
Colab notebook implementing a hybrid Convolutional Neural Network (CNN) + Long Short-Term Memory (LSTM) model for Parkinson’s Disease detection.

efficientnet_model.ipynb:
Colab notebook implementing EfficientNet-based transfer learning approach for classification between healthy and Parkinson’s-affected individuals.

Dataset
The dataset used involves handwriting data related to spiral and other tasks, commonly used in Parkinson's disease research. Data preprocessing, augmentation, and splitting were performed before training the models.

(Note: Dataset loading code is included inside the notebooks.)

Results
Model	Accuracy	Precision	Recall	F1-Score
CNN + LSTM Model	50%	0.25	0.50	0.33
EfficientNet Model	50%	0.25	0.50	0.33
Custom Hybrid Model	87%	0.87	0.87	0.87
The Custom Hybrid Model significantly outperforms the CNN+LSTM and EfficientNet models, demonstrating high accuracy and reliability for PD detection based on handwriting patterns.

Confusion matrices and classification reports for each model are included in the respective notebooks.

Technologies Used
Python 3

TensorFlow / Keras

Google Colab

Scikit-learn

EfficientNet Pre-trained Models

Numpy, Matplotlib, Seaborn

How to Run
Open the .ipynb files using Google Colab.

Upload or link the dataset as required.

Execute the cells sequentially to train and evaluate the models.

Analyze the results and confusion matrices provided.

References
The models and approaches are built based on literature and research from various sources, including:

Deep Learning for Health Informatics

EfficientNet: Rethinking Model Scaling

LSTM networks for sequence data

Parkinson’s Disease handwriting analysis research papers

Transfer learning methodologies

(For complete references, please see the Research Paper References section in the documentation.)

Future Work
Expand the dataset with more diverse handwriting samples.

Implement additional architectures such as Transformers for time-series handwriting data.

Optimize hyperparameters for better generalization.

Deploy the best-performing model as a lightweight web or mobile application for real-world PD screening.

Acknowledgment
Special thanks to [Your Institution or Research Lab] and all participants who contributed data for this study.
