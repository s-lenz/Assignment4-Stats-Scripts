# Overview
The purpose of this repository is to document my walk through of the SciPy tutorial and store the graphs.

# Assignment 4 – Python Statistics Walkthrough

This repository contains a Jupyter notebook that walks through statistical analysis in Python, based on exercises from the SciPy Lecture Notes. The goal is to practice applying common statistical and plotting techniques that will be useful in future data analysis labs.

## Source

Tutorial followed:
https://scipy-lectures.org/packages/statistics/index.html

## Getting Started

### Clone the Repository

```
git clone https://github.com/s-lenz/Assignment4-Stats-Scripts
cd Assignment4-Stats-Scripts
```

### Create the Conda Environment

```
conda env create -f assignment4_env.yml
conda activate stats-env
```

### Packages included
- Python 3
- Scipy
- Pandas
- Numpy
- OS
- Seaborn
- MatPlotLib

## Calculations performed
Performed basic statistical analysis including group means, standard deviations, and cross-tabulations. Applied hypothesis testing (t-tests, Mann-Whitney U, Wilcoxon, chi-squared tests), computed correlations, and built linear regression models using statsmodels to explore relationships while adjusting for covariates.

## Notes
- Each code block from the SciPy tutorial should be placed in its own notebook cell.
- Include **detailed comments** for every code example.
- Use **markdown cells** to structure and explain each section.
- If additional Python packages are required, install them and update the `environment.yml` or `requirements.txt` file accordingly.

- ## License
This repository is intended for educational use only.

## Acknowledgments
Based on exercises from:
https://scipy-lectures.org/packages/statistics/index.html
© The SciPy Lecture Notes authors.
