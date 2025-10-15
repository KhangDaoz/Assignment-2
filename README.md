# Deep Learning for Image Classification

This repository contains the source code and report for a project focused on building and evaluating a Convolutional Neural Network (CNN) for image classification. The model is trained on the CIFAR-10 dataset and then tested against custom images to evaluate its generalization performance.

## 📝 Project Overview

This project provides an end-to-end demonstration of a deep learning workflow for image classification. The key stages are implemented in Jupyter Notebooks and include:

  * **Data Loading & Preprocessing:** Loading the CIFAR-10 dataset, normalizing pixel values, and preparing it for training.
  * **Model Architecture:** Designing and building a Convolutional Neural Network (CNN) using TensorFlow/PyTorch.
  * **Training & Validation:** Training the model on the training set while monitoring its performance on a validation set.
  * **Evaluation:** Assessing the final model's accuracy and performance on the unseen test set.
  * **Inference:** Using the trained model to make predictions on new, custom images not from the original dataset.

A detailed analysis of the methodology and results is available in the final report.

## 📂 Repository Structure

```
.
├── Report/
│   ├── LaTeX Report/
│   └── PythonReport.pdf
├── SourceCode/
│   ├── Non-CIFAR_images/
│   ├── Assignment_2.ipynb
│   └── README.md
└── README.md
```

  * **`Report/`**: Contains the final PDF report and its LaTeX source files.
      * `PythonReport.pdf`: A comprehensive document detailing the project's methodology, architecture, results, and conclusions.
  * **`SourceCode/`**: Contains all Python code and related assets.
      * `Non-CIFAR_images/`: Custom images used to test the model's generalization capabilities.
      * `Assignment_2.ipynb`: The main Jupyter Notebook detailing the complete end-to-end process: data exploration, model building, training, and evaluation.

## 🚀 Getting Started

To get a local copy up and running, follow these simple steps.

### Prerequisites

You will need Python 3 and a standard data science environment. The key libraries are:

  * Jupyter Notebook / JupyterLab
  * TensorFlow or PyTorch
  * NumPy
  * Matplotlib
  * Scikit-learn

You can install all dependencies using pip:

```sh
pip install jupyterlab numpy matplotlib scikit-learn tensorflow
```

### Installation

1.  **Clone the repository:**
    ```sh
    git clone https://github.com/KhangDaoz/Assignment-2.git
    ```
2.  **Navigate to the project directory:**
    ```sh
    cd Assignment-2
    ```

## Usage

The main logic is contained within the Jupyter Notebooks.

1.  **Launch Jupyter Lab:**
    ```sh
    jupyter lab
    ```
2.  **Run the Notebooks:**
      * Navigate to the `SourceCode/` directory.
      * Open **`Assignment_2.ipynb`** to review the complete model development lifecycle from scratch.

## 📈 Results

The final model achieves an accuracy of **80%** on the CIFAR-10 test set. For a detailed breakdown of performance, including the confusion matrix, classification report, and an analysis of how the model performed on the custom `Non-CIFAR_images`, please see the full report in `Report/PythonReport.pdf`.
