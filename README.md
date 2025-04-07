# HW2_2210357124_idilsevis
This project implements a decision tree classifier on the  Banknote Authentication dataset. The goal is to classify banknotes as authentic or fake using four statistical features extracted from images: variance, skewness, kurtosis, and entropy.

# ELE489 - Homework 2: Decision Tree on Banknote Authentication Dataset

## Dataset
- Source: [UCI ML Repository](https://archive.ics.uci.edu/dataset/267/banknote+authentication)
- 1372 instances, 4 numerical features, 1 binary class label

## Tasks 
- Model training with `DecisionTreeClassifier`
- depth, splitting, criterion
- Evaluation (accuracy, precision, recall, F1-score, confusion matrix)
- Tree visualization and feature importance analysis

## Libraries Used
- pandas, numpy
- matplotlib, seaborn
- scikit-learn

## How to Run
1. Open `decision_tree.ipynb` in Google Colab
2. Run all cells in order
3. Modify parameters in model training section to test other configurations

## Result
Decision trees provided a good balance between interpretability and performance for this dataset. Features like variance and skewness were most important in classification.

5. Open `decision_tree.ipynb` and run all cells 

### Run Local

1. Clone the repository:
```bash
git clone https://github.com/idilsevis/HW2_2210357124_idilsevis.git
cd HW2_2210357124_idilsevis
```
```bash
pip install pandas numpy matplotlib seaborn scikit-learn
```
```bash
jupyter notebook decision_tree.ipynb
```
