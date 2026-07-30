# Handwritten Digit Recognition using Artificial Neural Networks (ANN)

## Objective

The objective of this project is to develop an Artificial Neural Network (ANN) model to recognize and classify handwritten digits (0–9) using the MNIST dataset.

---

## Dataset

MNIST Handwritten Digits Dataset

https://www.kaggle.com/datasets/oddrationale/mnist-in-csv

---

## Libraries Used

- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- TensorFlow / Keras

---

## Methodology

1. Loaded the MNIST dataset using Pandas.
2. Displayed the first five records.
3. Identified the input features and target variable.
4. Displayed the dataset dimensions and summary information.
5. Displayed one sample handwritten digit using Matplotlib.
6. Checked for missing values and removed incomplete records.
7. Separated the input features and target variable.
8. Normalized pixel values to the range 0–1.
9. Split the dataset into 80% training and 20% testing.
10. Converted target labels into categorical format using One-Hot Encoding.
11. Built an Artificial Neural Network (ANN) with:
    - Input Layer
    - Hidden Layer 1: 128 Neurons (ReLU)
    - Hidden Layer 2: 64 Neurons (ReLU)
    - Output Layer: 10 Neurons (Softmax)
12. Compiled the model using the Adam optimizer and Categorical Crossentropy loss function.
13. Trained the model for 10 epochs.
14. Predicted handwritten digits on the test dataset.
15. Evaluated the model using Accuracy, Confusion Matrix, and Classification Report.
16. Visualized the model performance using Accuracy vs Epoch and Loss vs Epoch graphs.

---

## Model Architecture

- **Input Layer:** 784 Input Features
- **Hidden Layer 1:** 128 Neurons (ReLU)
- **Hidden Layer 2:** 64 Neurons (ReLU)
- **Output Layer:** 10 Neurons (Softmax)
- **Optimizer:** Adam
- **Loss Function:** Categorical Crossentropy
- **Evaluation Metric:** Accuracy

---

## Results

- Successfully classified handwritten digits (0–9) using an Artificial Neural Network.
- Achieved high classification accuracy on the test dataset.
- The confusion matrix showed that most handwritten digits were correctly classified.
- Training and validation accuracy increased consistently over epochs, while the loss decreased.
- The ANN effectively learned complex patterns from pixel values and produced reliable predictions.

---

## Conclusion

The Artificial Neural Network (ANN) successfully classified handwritten digits from the MNIST dataset with high accuracy. The hidden layers enabled the model to learn complex patterns from the input images, resulting in effective digit recognition. Deep Learning offers a significant advantage over traditional Machine Learning by automatically extracting meaningful features from raw data without manual feature engineering. However, ANN models generally require more computational resources and training time than traditional machine learning algorithms. Overall, this project demonstrates that ANN is a powerful and reliable technique for handwritten digit recognition and image classification tasks.
