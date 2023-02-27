# Notebooks
This folder contains Jupyter notebooks with code for each step of the hyperspectral image analysis process.

## Usage
To use these notebooks, simply open them in Jupyter Notebook or Colab and run the cells sequentially. Each notebook is self-contained and includes example code. The input is dataframe of your data and the output is dataframe after the proccessing so you can export it to CSV and load it to the next phase.

## Contents
The following notebooks are included in this folder:

* **Denoise_HSI.ipynb:** Notebook explore how to clean up noisy hyperspectral images using 3 popular techniques.
* **Data_Transformation_HSI.ipynb**: Notebook explore various data transformations and standardization techniques commonly used in hyperspectral image analysis.
* **Feature_Selection folder**: Folder contain several methods to select relevant bands.
* **Feature_Extraction folder**: Folder contain several methods to reduce dimensions of the data.
* **ML_Hyperparameters_Tuning_HSI.ipynb**: Notebook for hyperparameter tuning using grid search.
* **Predict_ML_on_Image_HSI.ipynb**: Notebook for load models and making predictions on new hyperspectral images.
