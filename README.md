# Unsupervised Learning Project

This repository contains the Colab notebook and supporting data used for the Unsupervised Learning project. The main component of the work is the written report; this repository provides the code used for analysis and exploration.

## Repository Structure
Unsupervised-Learning-Project/
│
├── Survey Data/                # CSV data files (2017–2021)
├── unsupervised_learning.ipynb # Colab notebook
└── README.md                   # Project information

## Running the Notebook in Google Colab

You can open the notebook directly in Google Colab using the link below:

[![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/cewgs/Unsupervised-Learning-Project/blob/main/unsupervised_learning.ipynb)

Once opened, run the following setup cell at the top of the notebook to clone the repository and install the required package:
```python
# Setup
!git clone https://github.com/cewgs/Unsupervised-Learning-Project.git
%cd Unsupervised-Learning-Project
!pip install -q gower
After that, all code cells should run as intended.
Data Source
The mental health survey data used in this project is available at: https://osmhhelp.org/research.html
The CSV versions of these datasets (2017–2021) are included in this repository under the Survey Data folder for reproducibility.
