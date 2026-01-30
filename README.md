# KNN---Handwritten-Digit-Classification
This project applies the **K-Nearest Neighbors (KNN)** algorithm to the **MNIST handwritten digit dataset**.   Steps include loading the dataset, visualizing samples, preprocessing with scaling, training KNN with different K values, and evaluating performance using accuracy, confusion matrix, and sample predictions.

## 📂 Dataset
- **Primary:** MNIST dataset (IDX files: `train-images.idx3-ubyte`, `train-labels-idx1-ubyte`, `t10k-images.idx3-ubyte`, `t10k-labels-idx1-ubyte`)
- **Alternative:** `sklearn.datasets.load_digits()` (smaller dataset)

## ⚙️ Tools & Libraries
- Python (Google Colab)
- NumPy
- Matplotlib / Seaborn
- Scikit-learn

## 🚀 Steps Implemented
1. **Data Loading**  
   Parsed MNIST IDX files into NumPy arrays for training and testing.
   
2. **Visualization**  
   Displayed sample digit images with their labels to confirm dataset integrity.

3. **Preprocessing**  
   - Flattened 28×28 images into 784‑length vectors.  
   - Applied `StandardScaler` for feature scaling (important for distance-based algorithms like KNN).

4. **Model Training**  
   - Trained KNN classifier with multiple values of K (`3, 5, 7, 9`).  
   - Recorded accuracy for each K.

5. **Evaluation**  
   - Plotted **Accuracy vs K** graph to determine the best K.  
   - Generated **Confusion Matrix** to analyze misclassifications.  
   - Displayed 5 sample test images with predicted vs true labels.

## 📊 Results
- **Best K:** (replace with your result, e.g. `K=3`)  
- **Accuracy:** (replace with your accuracy, e.g. `0.9452`)  
- **Confusion Matrix:** Shows most digits classified correctly, with minor confusion between visually similar digits (e.g. 4 vs 9).  

## 📈 Plots
- Accuracy vs K
<img width="593" height="455" alt="download" src="https://github.com/user-attachments/assets/1b55c80d-29fb-4a20-ac94-37e6ddec7006" />

- Confusion Matrix (heatmap)
<img width="658" height="547" alt="download" src="https://github.com/user-attachments/assets/5d1eefa9-07e3-415e-be0f-aa736cbb141a" />
 
- Sample predictions (images with true vs predicted labels)
<img width="389" height="411" alt="download" src="https://github.com/user-attachments/assets/b4da1a7c-dd2f-4a47-b9c0-155ed8e922ca" />


## 🎯 Learning Outcome
- Understood how **KNN uses distance metrics** for classification.  
- Learned why **feature scaling** is critical for KNN.  
- Practiced **hyperparameter tuning** (choosing K).  
- Gained experience in evaluating models using accuracy and confusion matrix.
