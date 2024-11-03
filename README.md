# Histopathologic-Cancer-Detection
Project to detect metastatic cancer in pathology images using CNN

This project aims to detect metastatic cancer in pathology images by classifying small image patches as cancerous or non-cancerous using a Convolutional Neural Network (CNN).

## Project Overview
- **Dataset**: Images are taken from the Kaggle competition [Histopathologic Cancer Detection](https://www.kaggle.com/c/histopathologic-cancer-detection).
- **Objective**: Develop a binary classifier to identify cancerous tissue from non-cancerous tissue.
- **Model**: A custom CNN architecture trained on the provided dataset.

## Project Structure
- `Histopathologic-Cancer-Detection.ipynb`: The Jupyter Notebook containing the code for data exploration, model training, evaluation, and submission preparation.
- `submission.csv`: The file containing final predictions submitted to Kaggle.
- `screenshot.png`: A screenshot of the Kaggle submission results showing public and private scores.
- `requirements.txt`: List of dependencies required to run the notebook (if applicable).

## Results
The model achieved the following results on the Kaggle test set:
- **Public Score**: 0.8202
- **Private Score**: 0.7554

Although the submission was marked as "Late Submission" on Kaggle, these scores provide insight into the model's performance.

## Instructions
1. **Clone this repository**:
   ```bash
   git clone https://github.com/yourusername/Histopathologic-Cancer-Detection.git
   cd Histopathologic-Cancer-Detection
## Thanks to Kaggle for hosting the competition and providing the data.
