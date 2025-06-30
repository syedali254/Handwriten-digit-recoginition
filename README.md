# Handwriten-digit-recoginition
This project trains a model on the famous Digits dataset and evaluates it with test data, visualizing the results.

### 1.Clone the repository or directly import the code file


### 2. Create Virtual Environment (Optional but recommended)

python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate


### 3. Install Requirements

pip install -r requirements.txt


Or manually install:

pip install scikit-learn matplotlib


## ▶️ How to Run

python digit_recognition.py


You’ll see a digit displayed, followed by prediction output:

 Model Accuracy on Test Data: 97.50%
🔍 Predicted digit: 6
🧾 Actual digit   : 6


## 🔍 Main Components
- **Dataset**: Uses `load_digits()` from `sklearn.datasets`.
- **Model**: `LogisticRegression` from Scikit-learn.
- **Train/Test Split**: 80/20 split using `train_test_split()`.
- **Visualization**: Digit image shown via `matplotlib.pyplot`.
- **Evaluation**: Accuracy of the model is printed, and a sample prediction is compared.

## 📸 Sample Output
- A random digit is shown.
- The model predicts its value.
- Both the predicted and actual values are printed.



## 📬 Contributing
Pull requests are welcome! For major changes, please open an issue first.



**Author**: Muhammad Ali

> This project is a great intro to machine learning with Python and Scikit-learn. Happy coding!

