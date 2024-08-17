# Edge-IA
Log Error Detection and Classification Using Neural Networks This project focuses on detecting and classifying error logs from system log files using machine learning techniques. The project includes several key stages, from preprocessing the raw log data to training a deep neural network model to accurately classify the logs.

Key Features:
Log Preprocessing: Extracts and filters error-related log lines from raw log files.
Log Parsing and Labeling: Analyzes log lines to extract structured information (e.g., date, host, service, message) and labels them based on their error status.
Data Vectorization and Balancing: Utilizes TF-IDF vectorization to convert log messages into numerical features, and applies SMOTE for oversampling to handle class imbalance.
Neural Network Model: Trains a deep learning model with multiple dense layers to classify log messages. The model achieves high accuracy and low loss, making it effective for real-world applications.
Performance Evaluation: The model is rigorously evaluated on a test dataset, demonstrating a 99.90% accuracy rate.
