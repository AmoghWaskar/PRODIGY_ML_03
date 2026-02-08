# PRODIGY_ML_03
This project implements a Support Vector Machine (SVM) based image classification system to distinguish between cat and dog images. Histogram of Oriented Gradients (HOG) is used for feature extraction, and the model is trained and evaluated using Google Colab on a reduced version of the dataset for efficient execution.

- Images were loaded from Google Drive and preprocessed.
- Due to computational constraints, a subset of the dataset was used.

---

## ⚙️ Technologies Used
- Python
- Google Colab
- OpenCV
- Scikit-image
- Scikit-learn
- Matplotlib

---

##  Methodology

### 1. Data Preprocessing
- Images resized to a fixed size (48×48)
- Converted to grayscale
- Corrupted images skipped safely

### 2. Feature Extraction
- Histogram of Oriented Gradients (HOG) used to extract shape and edge features
- Reduced feature dimensionality for faster execution

### 3. Model Training
- Support Vector Machine with linear kernel (`LinearSVC`)
- Dataset split into training and testing sets (80:20)

### 4. Model Evaluation
- Accuracy score
- Confusion matrix
- Visual inspection of predictions

---

##  Results
- Achieved ~70 accuracy on the test dataset
- Confusion matrix shows balanced classification performance
- Sample predictions demonstrate correct classification for most images

---

##  Visualizations
- Confusion Matrix
- Sample Image Predictions
- Class Distribution Plot

---

##  How to Run
1. Upload the dataset to Google Drive
2. Mount Drive in Google Colab
3. Run cells sequentially to extract features and train the model
4. Evaluate results using provided visualization code

---

##  Conclusion
This project highlights the effectiveness of classical machine learning techniques like SVM when combined with handcrafted features such as HOG. While deep learning models may achieve higher accuracy, SVM provides a computationally efficient and interpretable alternative for image classification tasks.

---

##  Future Improvements
- Use full dataset for improved accuracy
- Hyperparameter tuning for SVM
- Compare performance with CNN-based models
- Extend to multi-class image classification

---

##  Author
**Amogh Waskar**

