# Diagnosis of Cardiac Arrhythmia with PCA and MLP

This repository contains the code for diagnosing Cardiac Arrhythmia using PCA (Principal Component Analysis) and MLP (Multi-Layer Perceptron) for classification.

## Files

- `Code.ipynb`: Jupyter Notebook file containing the Python code for the project.
- `arrhythmia.data`: Dataset file containing the cardiac arrhythmia data.
- `arrhythmia.names`: File providing information about the dataset.

## Project Overview

The `Code.ipynb` Jupyter Notebook file implements the following steps for diagnosing Cardiac Arrhythmia:

1. **Data Preparation**: The dataset is downloaded from the provided link and read into the notebook.
2. **Data Preprocessing**: The data is preprocessed, including handling missing values and performing necessary transformations.
3. **Train-Test Split**: The data is split into training and testing sets for model evaluation.
4. **Dimension Reduction with PCA**: PCA is applied to reduce the dimensionality of the data while preserving 0.995 of the variance. The dimension is reduced from 280 to 43.
5. **Binary Classification**: MLP is used for binary classification to distinguish between normal and arrhythmia cases. Confusion matrices are shown for both the training and testing sets.
6. **Multiclass Classification**: MLP is employed for multiclass classification to classify the arrhythmia types using categorical cross-entropy. There are 16 classes, with 1 representing normal and 15 representing arrhythmia types.

Please refer to the `Code.ipynb` notebook for detailed implementation. Feel free to modify the code and adapt it to your specific requirements or dataset. If you have any questions or need further assistance, please don't hesitate to reach out.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.
