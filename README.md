# Traffic Sign Classifier using SVM and HOG

This project builds a machine learning pipeline to classify traffic signs using Support Vector Machines (SVM) and HOG (Histogram of Oriented Gradients) features. The model is trained and tested on images from a traffic dataset.

---

## Features
- **Image preprocessing**: Sharpening and smoothing
- **Feature extraction**: HOG descriptors
- **Classifier**: SVM
- **Visualization**: Matplotlib image grid with prediction titles

---

## How to Run This Project on Kaggle

>  This notebook is designed to run on **Kaggle Kernels**. Follow these steps:

### 1. Upload to Kaggle
- Go to [https://www.kaggle.com/code](https://www.kaggle.com/code) and click **"New Notebook"**.
- In the editor, click the folder icon on the left and choose **"Upload"** > upload `traffic.ipynb`.

### 2. Connect the Dataset
- Click the “Add data” button on the right panel.
- Navigate to or search for your dataset https://www.kaggle.com/datasets/andrewmvd/road-sign-detection and click **Add**.
- This will mount the dataset..

### 3. Make Sure Paths Match
In your notebook, check that the image paths match the dataset:

```python
images = '/kaggle/input/road-sign-detection/images'
labels = '/kaggle/input/road-sign-detection/annotations'
