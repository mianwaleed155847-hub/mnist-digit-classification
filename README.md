#  MNIST Digit Classification

A complete end-to-end Machine Learning classification project
built on the famous MNIST dataset of 70,000 handwritten digits.

##  Dataset
- **Source:** Scikit-Learn — fetch_openml
- **Images:** 70,000 handwritten digits
- **Classes:** 0 to 9
- **Features:** 784 pixels (28x28)
- **Training Set:** 60,000 images
- **Test Set:** 10,000 images

##  Project Workflow
1. Dataset Loading and Exploration
2. Binary Classification — 5 ya Not 5
3. Confusion Matrix Analysis
4. Precision, Recall aur F1 Score
5. Precision/Recall Tradeoff
6. ROC Curve aur AUC Score
7. Multiclass Classification — 0 to 9
8. Error Analysis
9. Multilabel aur Multioutput Classification

##  Models Used
| Model | Task | Accuracy |
|-------|------|---------|
| SGD Classifier | Binary — 5 ya Not 5 | 95.7% |
| SGD Classifier | Multiclass — 0 to 9 | 87%+ |
| KNN Classifier | Multilabel | F1: 0.97+ |
| KNN Classifier | Multioutput — Denoising | Visual |

##  Key Results
- **Binary Precision:** 84%
- **Binary Recall:** 65%
- **Binary F1 Score:** 73%
- **AUC Score:** 0.95+
- **Multiclass Accuracy:** 87%+

##  Libraries Used
- Python 3
- NumPy
- Scikit-Learn
- Matplotlib

##  How to Run

1. Install libraries

pip install -r requirements.txt

2. Open Jupyter Notebook

jupyter notebook mnist_classification.ipynb

##  Author
Waleed Ahmad
BSDS Student(2nd Semester) — Riphah International University Faisalabad
