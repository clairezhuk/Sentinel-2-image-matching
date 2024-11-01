# Sentinel-2 Image Matching

This repository contains a Jupyter Notebook for matching Sentinel-2 images. The project utilizes a dataset obtained from Kaggle, where the development and execution of the model took place.

## Contents

- **sentinel-2-image-matching.ipynb**: This Jupyter Notebook includes the complete implementation of the image matching process, including data preparation, model building, and training procedures.

## Dataset

The dataset used in this project is sourced from Kaggle and consists of Sentinel-2 images, organized into directories by date and location. It also includes GeoJSON files containing vector shapes for various objects within the locations.

## Current Status

At this stage, the repository contains only the Jupyter Notebook. Further improvements and developments are planned, including enhancements to the keypoint detection algorithm and dataset optimization.

## Installation

To run the notebook, ensure you have the following packages installed:

- TensorFlow
- Pandas
- NumPy
- OpenCV
- scikit-learn
- tqdm
- GeoPandas (if applicable)

You can install the necessary packages using pip:

```bash
pip install tensorflow pandas numpy opencv-python scikit-learn tqdm geopandas
