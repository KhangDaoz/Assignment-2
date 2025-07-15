# Assignment 2: Image Classification with Deep Learning

This repository contains the source code, notebooks, and reports for an image classification project. The primary goal is to build and evaluate a model capable of classifying images, likely using a dataset such as CIFAR-10, and testing it against other images.

## 📝 Description

This project explores the fundamentals of building a deep learning model for image classification. The core tasks are implemented in Jupyter Notebooks and include data loading, preprocessing, model architecture definition, training, and evaluation. A detailed analysis and summary of the results are available in the PDF report.

## 📂 Project Structure

Here is an overview of the files and directories within this repository:

```
.
├── Report/
│   ├── LaTeX Report/
│   └── PythonReport.pdf
├── SourceCode/
│   ├── Non-CIFAR_images/
│   ├── Assignment_2.ipynb
│   ├── run_model.ipynb
│   └── README.md
└── README.md
```

* **`Report/`**: Contains the final reports for the assignment.
    * `PythonReport.pdf`: The main report detailing the methodology, results, and conclusions.
    * `LaTeX Report/`: Source files for the report.
* **`SourceCode/`**: Contains all the code and related assets.
    * `Non-CIFAR_images/`: A directory containing images not from the primary training dataset, used for testing the model's generalization.
    * `Assignment_2.ipynb`: The main Jupyter Notebook containing the complete workflow: data exploration, model building, training, and evaluation.
    * `run_model.ipynb`: A notebook likely used for loading a pre-trained model and running predictions on new images.

## 🚀 Getting Started

To run this project on your local machine, please follow the steps below.

### Prerequisites

You will need Python 3 and a standard environment for data science. The key libraries are:
* [Jupyter Notebook](https://jupyter.org/install) or [JupyterLab](https://jupyterlab.readthedocs.io/en/stable/getting_started/installation.html)
* [TensorFlow](https://www.tensorflow.org/install) or [PyTorch](https://pytorch.org/get-started/locally/)
* NumPy
* Matplotlib
* Scikit-learn

You can install these dependencies using pip:
```sh
pip install jupyterlab numpy matplotlib scikit-learn tensorflow
```

### Installation

1.  **Clone the repository:**
    ```sh
    git clone <your-repository-url>
    ```
2.  **Navigate to the project directory:**
    ```sh
    cd <your-repository-name>
    ```

## Usage

The primary workflow is contained within the Jupyter Notebooks in the `SourceCode/` directory.

1.  **Start Jupyter:**
    ```sh
    jupyter lab
    ```
2.  **Open and run the notebooks:**
    * Navigate to `SourceCode/` in the Jupyter interface.
    * Open `Assignment_2.ipynb` to see the full model development process.
    * Open `run_model.ipynb` to test the final trained model.

## Report

For a comprehensive understanding of the project, including the theoretical background, implementation details, and analysis of the results, please refer to the report located at: `Report/PythonReport.pdf`.
