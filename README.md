# FCCN for Pressure Drop Prediction
This project aims to predict the pressure drop using a FCCN. The dataset is normalized and split into two parts based on a pressure drop threshold (5000 Pa). Separate models are trained and evaluated for data below and above the threshold, then combined to evaluate overall performance.
## Features
- **Data Preprocessing:** Normalization of both input features and output labels.
- **Dataset Splitting:** Separation of data based on the absolute value of the pressure drop.
- **Model Architecture:** A fully connected neural network with dropout layers to prevent overfitting.
- **Training and Evaluation:** Implementation of training routines, evaluation metrics, and plotting of prediction results.

## Dependencies
- Python 3.7 or higher
- [PyTorch](https://pytorch.org/)
- [scikit-learn](https://scikit-learn.org/)
- [pandas](https://pandas.pydata.org/)
- [matplotlib](https://matplotlib.org/)

## Installation
1. **Clone the repository:**
   ```bash
   [git clone ](https://github.com/MontaCFD/Pressure-drop-prediction-using-FCNN.git)
   cd repository_name
