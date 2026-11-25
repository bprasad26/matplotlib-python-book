# Data Visualization Made Easy

## Creating Beautiful Charts in Python With Matplotlib

This repository contains the Jupyter notebooks, datasets, and images accompanying the book Data Visualization Made Easy.

Use these resources to follow the examples, experiment with the code, and practice the concepts discussed throughout the book.

## Repository Structure

matplotlib-python-book/
├── data/                 # Datasets used in the book
├── images/               # Images used in the notebooks
├── notebooks/            # Chapter-wise Jupyter notebooks
├── environment.yml       # Conda environment configuration
├── requirements.txt      # Main Python libraries and versions
└── README

## Getting Started

Follow the instructions below to set up your Python environment and run the notebooks.

### 1. Install Git

Git is required to clone the repository from GitHub. Download and install Git for your operating system: [Download Git](https://git-scm.com/install/)
After installation, open a terminal and verify it:

```
git --version
```
### 2. Install Conda

Conda is used to create and manage the Python environment required by the notebooks. We recommend installing Miniforge, which includes Conda and uses the conda-forge package repository.

[Install Miniforge](https://github.com/conda-forge/miniforge)

After installation, open a terminal and verify Conda:

```
conda --version
```

### 3. Clone the Repository

Open a terminal and run:

```
git clone https://github.com/bprasad26/matplotlib-python-book.git
```
This will downloads the repository to your computer. To navigate to the cloned repository directory:

```
cd matplotlib-python-book
```
Alternatively, you can also download the repository as a ZIP file from GitHub and extract it.

### 4. Create the Conda Environment

The repository includes an `environment.yml` file containing the Python version and required library versions.
Create the environment using:

```
conda env create -f environment.yml
```
Conda will resolve and install the required packages and their dependencies.

### 5. Activate the Environment

Once the installation is complete, activate the environment:
```
conda activate dataviz
```
### 6. Launch Jupyter Notebook

Run the following command in terminal to start the jupyter notebook.

```
jupyter notebook
```
Your default web browser will open the Jupyter Notebook interface. Navigate to the notebooks directory and open the chapter notebook you want to explore.
Keep these directories in their original locations to ensure that the notebooks can access the required files.

## Required Libraries

The Conda environment includes the following main Python libraries:

* Python 3.13
* Matplotlib
* NumPy
* Pandas
* Seaborn
* GeoPandas
* Jupyter Notebook
* ipympl
* yfinance
* highlight-text

The specific library versions are defined in `environment.yml`. The `requirements.txt` file also lists the main Python libraries and their versions.

## Updating the Repository

If you have already cloned the repository and want to download the latest changes, navigate to the repository directory and run:

```
git pull
```
## Feedback and Issues

If you find an error in the notebooks or encounter a problem while following the examples, please report it through the [GitHub Issues](https://github.com/bprasad26/matplotlib-python-book/issues) page.

Your feedback and suggestions are welcome.








