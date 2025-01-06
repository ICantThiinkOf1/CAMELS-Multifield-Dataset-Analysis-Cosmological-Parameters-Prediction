# CAMELS-Multifield-Dataset-Analysis-Cosmological-Parameters-Prediction
This repository contains Python notebooks analyzing a subset of the **CAMELS Multifield Dataset (CMD)**. The goal of this project is to predict fundamental cosmological parameters, such as **Ωm** (fraction of matter) and **σ8** (distribution smoothness), using machine learning techniques.

## Project Overview:
The dataset includes simulated astrophysical fields like gas density, temperature, and dark matter, all generated from the **IllustrisTNG** simulation. The project focuses on predicting cosmological parameters from single and multiple maps of these fields.

## Machine Learning Tasks:
- **Single-map Prediction**: Train a model to predict cosmological parameters from one astrophysical field map.
- **Multiple-map Prediction**: Train a model to predict cosmological parameters from several fields at once.
- **Generative Modeling**: Explore generative algorithms to predict one field from another.

## Data:
The dataset consists of multiple 2D maps of different astrophysical fields:
- Gas density (**Mgas**)
- Gas temperature (**T**)
- Dark matter density (**Mcdm**)
- Stellar mass density (**Mstar**)
- And many others...

Each map corresponds to a set of simulation parameters, with **15 images** for each parameter combination.

## Potential Extensions:
- Train a model on one field and predict cosmological parameters for other fields.
- Develop generative models to map one field to another.

## Requirements:
- Python 3.x
- Jupyter Notebook
- Libraries: `numpy`, `pandas`, `scikit-learn`, `tensorflow`, `matplotlib`, etc.
