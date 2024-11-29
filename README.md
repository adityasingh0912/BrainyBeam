
---

# Brainy Beam Interview Tasks

This repository contains solutions to the tasks assigned during the Brainy Beam interview process. Each task demonstrates the application of Python and data science concepts to solve real-world problems using the provided dataset, [100 Sales](https://www.kaggle.com/datasets/nishathakkar/100-sales).

---

## Dataset Used

- **Name**: [100 Sales Dataset](https://www.kaggle.com/datasets/nishathakkar/100-sales)
- **Description**: This dataset contains sales information with features like product categories, sales values, and other metadata.

---

## Tasks and Solutions

### 1. **Operations on Multi-Index**
   - **Objective**: Work with multi-index DataFrames and perform operations across different levels.
   - **Solution**:
     - Created a multi-index from the dataset.
     - Performed operations like level-wise aggregation and filtering.
     - Demonstrated merging and reshaping multi-index DataFrames.

---

### 2. **Applying Custom NumPy Universal Functions**
   - **Objective**: Create and apply a custom NumPy universal function (ufunc) to a NumPy array.
   - **Solution**:
     - Developed a custom `ufunc` for mathematical operations.
     - Applied the `ufunc` to transform numerical data in the dataset.

---

### 3. **Classification with Decision Tree and Random Forest**
   - **Objective**: Apply Decision Tree and Random Forest classifiers to predict categorical outcomes and optimize for good accuracy.
   - **Solution**:
     - Preprocessed the `100_sales.csv` dataset for training and testing.
     - Implemented models using `scikit-learn`.
     - Tuned hyperparameters to achieve the best accuracy.

---

### 4. **Multiple Y-Axes Sharing a Common X-Axis Plot**
   - **Objective**: Create a plot with multiple y-axes sharing a common x-axis.
   - **Solution**:
     - Used `matplotlib` to create a plot with multiple y-axes.
     - Visualized relationships between different features in the dataset over a common time or categorical axis.

---

### 5. **Matrix Factorization using Singular Value Decomposition (SVD)**
   - **Objective**: Implement matrix factorization using Singular Value Decomposition (SVD).
   - **Solution**:
     - Performed SVD using `numpy` on the dataset.
     - Reconstructed the matrix and analyzed the reduced dimensions.
     - Explained the importance of SVD in dimensionality reduction.

---

## Instructions to Run

1. Clone this repository:
   ```bash
   git clone <repository_url>
   cd <repository_folder>
   ```

2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

3. Download the dataset ([100_sales.csv](https://www.kaggle.com/datasets/nishathakkar/100-sales)) and place it in the project directory.

4. Run the Python files for individual tasks:
   - **Task 1**: Operations on Multi-Index
     ```bash
     python task1_multiindex.py
     ```
   - **Task 2**: Custom NumPy Universal Functions
     ```bash
     python task2_custom_ufunc.py
     ```
   - **Task 3**: Classification with Decision Tree and Random Forest
     ```bash
     python task3_classification.py
     ```
   - **Task 4**: Multiple Y-Axes Plot
     ```bash
     python task4_multiple_y_axes.py
     ```
   - **Task 5**: SVD Matrix Factorization
     ```bash
     python task5_svd.py
     ```

---

## Requirements

- Python 3.8+
- NumPy
- Pandas
- Scikit-learn
- Matplotlib

Install dependencies using:
```bash
pip install -r requirements.txt
```

---

## Results

- **Task 3 (Classification)**:
  - Achieved a strong accuracy with optimized Decision Tree and Random Forest models.
- **Task 5 (SVD)**:
  - Demonstrated effective matrix reconstruction and dimensionality reduction.

---

## License

This project is for interview purposes only and is not intended for commercial use.

---

