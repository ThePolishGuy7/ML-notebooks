# Machine Learning - Notebooks and Projects

This collection of projects was created during a university **"Machine Learning"** course. The repository documents the practical application of machine learning algorithms, deep learning, and data engineering. 

## Project Contents

Inside the notebooks, you will find a complete Data Science / ML workflow, including:
* **Exploratory Data Analysis (EDA)** and detailed **visualizations** to better understand the datasets.
* **Data preprocessing**, including strategies for handling missing values (**data imputation**).
* Designing and training **predictive models**.
* Creating automated workflows using **Pipelines** and custom **Transformers**.
* Building neural networks and Deep Learning models using **TensorFlow**.

---

## Environment Setup (Conda)

To run all the notebooks smoothly on your local machine, it is highly recommended to create a virtual environment using the Conda package manager. The following steps will install all the necessary packages, including `pandas`, `numpy`, `seaborn`, `matplotlib`, `scikit-learn`, and `tensorflow`.

### Step-by-Step Installation

1. Clone the repository and navigate to the project directory:
    ```bash
    git clone [https://github.com/ThePolishGuy7/ML-notebooks.git](https://github.com/ThePolishGuy7/ML-notebooks.git)
    cd ML-notebooks
    ```

2. Create a new virtual environment (e.g., named ml_env) with all the required libraries and Jupyter:
    ```bash
    conda create -n ml_env python=3.10 pandas numpy seaborn matplotlib scikit-learn tensorflow jupyter -y
    ```

3. Activate the environment:
    ```bash
    conda activate ml_env
    ```

4. Launch Jupyter Notebook or Jupyter Lab:
    ```bash
    jupyter notebook
    ```