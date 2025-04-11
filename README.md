# MNIST_Digit_Classification
This project is a simple implementation of a neural network to classify handwritten digits using the **MNIST dataset**. The model is built using **TensorFlow/Keras** and is suitable for beginners learning deep learning and model evaluation.

---

## 📌 What This Project Does

- Loads and preprocesses the **MNIST dataset** (images of digits 0–9)
- Builds a **basic neural network (MLP)** to classify the digits
- Trains the model on the training set
- Evaluates it on the test set
- Shows useful plots and metrics to understand how well the model performs

---

## 🧠 How It Works

1. **Data Loading**  
   Loads the dataset from Keras (60,000 training and 10,000 test images)

2. **Preprocessing**  
   - Normalizes pixel values (0–255 → 0–1)
   - Converts labels to one-hot encoded format

3. **Model Architecture**  
   - Flatten layer (to convert 2D images to 1D)
   - Dense layer with 128 neurons (ReLU)
   - Dense layer with 64 neurons (ReLU)
   - Output layer with 10 neurons (Softmax)

4. **Training**  
   The model is trained for a few epochs with validation on the test set

5. **Evaluation & Visualization**  
   - Accuracy and loss over epochs  
   - Confusion matrix  
   - Random digit samples with predictions

---

## 📷 Example Output

- ✅ Model Accuracy ~97%
- ✅ Training & Validation Accuracy Plots
- ✅ Confusion Matrix showing where the model confuses digits

---
