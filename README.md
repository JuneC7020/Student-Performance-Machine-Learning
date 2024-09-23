# Student Performance Machine Learning

This project uses machine learning algorithms to predict student performance based on demographic and academic data. The dataset used is sourced from the UCI Machine Learning Repository, and models like Neural Networks, Support Vector Machines (SVM), k-Nearest Neighbors (k-NN), and AdaBoost are implemented for classification tasks. SMOTE is applied to handle class imbalance, and various preprocessing steps are performed, including encoding categorical features and scaling numerical data.

## Project Structure

- **ML_A1Minjun_student_performance.ipynb**: Jupyter notebook containing the entire workflow for student performance prediction, including data preprocessing, model training, and evaluation.
- **data/**: Directory to store the Student Performance dataset (download instructions below).
- **results/**: Directory to store the results of the experiments, such as model performance metrics.

## Dataset

The Student Performance dataset is available on the UCI Machine Learning Repository. You can download it from the following link:
- [Student Performance Dataset](https://archive.ics.uci.edu/ml/datasets/Student+Performance)

Place the dataset in the `data/` folder before running the notebook.

## Requirements

### Libraries

The following Python libraries are required to run the project:

- Python 3.x
- NumPy
- Pandas
- Scikit-learn
- TensorFlow/Keras
- Matplotlib
- Seaborn (optional for visualizations)
- Imbalanced-learn (for SMOTE)

You can install the required libraries using the following command:

```bash
pip install numpy pandas scikit-learn tensorflow matplotlib seaborn imbalanced-learn
