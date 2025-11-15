---
# Chest X-ray Pneumonia Detection using Transfer Learning
---

---

## Project Overview

This project implements an a deep learning pipeline to classify chest X-ray images as either **NORMAL** or containing **PNEUMONIA**. It leverages transfer learning with the VGG16 model, is built using TensorFlow/Keras, and includes an interactive web interface for real-time predictions powered by Gradio.

Pneumonia is a serious lung infection that can be diagnosed with the help of chest X-rays. This project aims for detection process by training a Convolutional Neural Network (CNN) to distinguish between healthy and infected lungs.

---

## Dataset

This project uses the **Chest X-Ray Images (Pneumonia)** dataset available on Kaggle.

- **Source:** [Kaggle Dataset Link](https://www.kaggle.com/datasets/paultimothymooney/chest-xray-pneumonia)

## Getting Started

This project is designed to be run in a Google Colab environment to leverage free GPU resources.

### Prerequisites

- A Google Account (for Google Colab).
- A Kaggle Account.
- Your Kaggle API token (`kaggle.json` file). You can generate this from your Kaggle account settings (`Account` -> `API` -> `Create New API Token`).

---

### Installation & Setup

1.  **Clone the Repository (Optional):**

    ```bash
    git clone https://github.com/abt34/CNN---pneumonia_classifier.git
    cd your-repo-name
    ```

2.  **Open the Notebook in Google Colab:**
    - Upload the `cnn_pneumonia_classifier.ipynb` file to your Google Drive.
    - Open it with Google Colab.
3.  **Enable GPU Acceleration:**
    - In Colab, go to `Runtime` -> `Change runtime type`.
    - Select `T4 GPU` from the `Hardware accelerator` dropdown and click `Save`.
4.  **Open the Notebook in Google Colab:**
    - Upload the cnn_pneumonia_classifier.ipynb file to your Google Drive.
    - Open it with Google Colab.
5.  **Enable GPU Acceleration (Recommended):**
6.  **Run the First Code Cell:**
7.  **Upload Your kaggle.json File:**
8.  **Run the Remaining Cells:**
9.  **Use the Gradio App:**

## ![alt text](./Resource/test%20resualts/image.png)

![alt text](./Resource/test%20resualts/image%202.png)
