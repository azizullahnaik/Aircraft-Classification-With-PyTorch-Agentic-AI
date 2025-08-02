# Aircraft Classification With PyTorch
This project demonstrates a simple image classification task to identify military aircraft using a Convolutional Neural Network (CNN) built with PyTorch. It provides a complete end-to-end pipeline for training and evaluating the model.

## 🎯 Project Goals
Build and train a custom CNN model to classify images.

Identify whether an image contains a military aircraft or not.

Evaluate model performance using accuracy metrics.

Highlight the potential issue of overfitting and how to address it.

## 📂 Dataset
This project uses the Military Aircraft Detection Dataset, which contains:

A collection of images of various aircraft.

Corresponding CSV files with bounding box annotations.

The data is accessed and processed directly within the code (no manual download needed).

## ⚙️ Main Steps
Load and explore the dataset, including images and annotations.

Create a custom AircraftDataset class for efficient data handling.

Split the data into training and testing sets.

Define and train a custom CNN (AircraftCNN) model.

Evaluate the model's performance on the unseen test set to check for overfitting.

Print final test accuracy to determine the model's generalization capability.

## 📊 Output Example
Training Performance: High training accuracy (e.g., 100%) and near-zero loss, which indicates the model has learned the training data well but may be overfitting.

Evaluation Performance: The final test accuracy will be the key metric to determine if the model is ready for real-world application or if further improvements are needed.
