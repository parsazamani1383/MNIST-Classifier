# MNIST Classifier

A complete Machine Learning pipeline for classifying handwritten digits using the **MNIST dataset**.  
This project demonstrates the full process of data preparation, visualization, model training, and evaluation — all in a single, well‑structured notebook.

---

## 👤 Author

**Parsa Zamani**  
Computer Engineering Student  
📧 Email: [parsazamani.uok@gmail.com](mailto:parsazamani.uok@gmail.com)  
🌐 GitHub: [github.com/parsazamani1383](https://github.com/parsazamani1383)

---

## 🧠 Project Overview

The **MNIST dataset** contains 70,000 images of handwritten digits (0–9), each of size **28×28 pixels**.  
In this notebook, we build and train a baseline machine learning model to classify these digits.

**Workflow steps:**
- Data loading and structure inspection  
- Visualizing sample images  
- Class distribution analysis  
- Splitting data into train/test sets  
- Feature scaling (normalization)  
- Training a baseline model (Logistic Regression)  
- Model evaluation

---

## ⚙️ Technologies Used

- Python 3
- NumPy
- Pandas
- Matplotlib
- scikit‑learn

---

## 📊 Dataset

**Source:** [MNIST handwritten digits](https://www.openml.org/d/554)  
**Size:** 70,000 images — each represented by 784 features (28×28 p  
**Classes:** 10 (digits 0–9)

Loaded with:
```python
from sklearn.datasets import fetch_openml
🤖 Machine Learning Model

Model: Logistic Regression

    Multi‑class classification (digits 0–9)
    Solver: lbfgs
    max_iter=1000 for convergence
    stratify=y to keep class balance during split

This baseline model provides initial performance metrics before moving to more advanced algorithms.
📁 Project Structure

                                                                    text
MNIST-Classifier
│
├── mnist_classifier.ipynb
└── README.md

📈 Example Tasks in the Notebook

    Visualize 9 random handwritten digits
    Analyze class distribution (balanced check)
    Scale pixel values from 0–255 to 0–1
    Train the Logistic Regression model
    Evaluate accuracy on the test set

🚀 How to Run

    Clone the repository:

                                                                    bash
   git clone https://github.com/parsazamani1383/MNIST-Classifier.git
   

    Enter the project directory:

                                                                    bash
   cd MNIST-Classifier
   

    Launch Jupyter Notebook:

                                                                    bash
   jupyter notebook
   

    Open mnist_classifier.ipynb and run all cells step by step.

🔮 Future Improvements

    Compare multiple classifiers (SVM, Random Forest, etc.)
    Add performance metrics (precision, recall, F1‑score)
    Visualize Confusion Matrix
    Integrate a simple Neural Network / CNN
    Save the trained model for deployment

🪪 License

MIT License — free to use, modify, and share for learning and research.
