# Astronomical Classification with DESI spectroscopic data

This project analyzes spectroscopic data from the DESI survey to classify different types of astronomical objects.

## How to Run
Copy the notebook to Google Colab, set the runtime to Python, and run it step by step.

## File Descriptions
DESI_preprocess.ipynb: Data preprocessing notebook. Run this first. It will download the DESI dataset from the official website. The dataset is large — make sure your Google Drive has enough space.

DESI_data_explore.ipynb: Exploratory data analysis on a small subset of the dataset.

DESI_spectype.ipynb: Classifies astronomical objects (e.g., stars, galaxies, quasars) using a random sample of the data and a Random Forest model.

DESI_subtype.ipynb: Further classifies stellar subtypes using LightGBM.

data_and_model/: Contains data samples and trained models. Note: Full datasets are too large to upload to GitHub.

DESI.pdf: Final report for this project.

## Reference

DESI Collaboration et al. (2016). The DESI Experiment Part I: Science, Targeting, and Survey Design. arXiv:1611.00036
