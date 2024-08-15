# Foot_Ulcer_Segmentation_Ensemble_Approch

---

# Foot Ulcer Segmentation using U-Net, U-Net++, and SegNet

Welcome to the Foot Ulcer Segmentation repository! This project focuses on the segmentation of foot ulcers from medical images using deep learning models like U-Net, U-Net++, and SegNet. To enhance the segmentation results, we have used wavelet transform for image preprocessing and averaged the outputs of all models.

## Project Overview

### Objectives

- **Foot Ulcer Segmentation:** Accurately segment foot ulcers from medical images using three different deep learning models: U-Net, U-Net++, and SegNet.
- **Image Preprocessing:** Utilize wavelet transform to preprocess the input images, improving the clarity and enhancing features relevant for segmentation.
- **Model Averaging:** Combine the strengths of all three models by averaging their segmentation outputs, leading to a more robust and accurate final prediction.

### Models Used

- **U-Net:** A widely-used convolutional network architecture for biomedical image segmentation.
- **U-Net++:** An advanced version of U-Net with nested and dense skip pathways, improving the segmentation accuracy.
- **SegNet:** A deep learning model for semantic segmentation, designed with an encoder-decoder architecture.

### Image Processing Techniques

- **Wavelet Transform:** A powerful tool for image preprocessing, wavelet transform helps in decomposing the image into different frequency components, allowing for noise reduction and feature enhancement.

## Installation

### Requirements

Ensure you have Python 3.x installed, along with the following packages:

```bash
pip install tensorflow keras opencv-python scikit-image pywavelets numpy
```

### Repository Setup

Clone the repository and navigate to the project directory:

```bash
git clone https://github.com/mahatalakshmi/Foot_Ulcer_Segmentation_Ensemble_Approch.git
cd Foot_Ulcer_Segmentation_Ensemble_Approch
```

## Usage

### 1. Preprocess the Images

Preprocess the input images using wavelet transform.
### 2. Train the Models

You can train the U-Net, U-Net++, and SegNet models using the provided training scripts:

```bash
python file.py
```
Architecture:

![image](https://github.com/user-attachments/assets/560c2001-f125-4214-8d84-e822fb4fd0f5)

### 3. Perform Segmentation

To perform segmentation and average the results of the above model

### 4. Evaluate the Models

Evaluate the performance of the models using common metrics like Dice coefficient, Intersection over Union (IoU), precision and recall.
## Results

Results showing the original images, processed images, and final segmentation masks.

![image](https://github.com/user-attachments/assets/37948d1a-fb6c-420c-bc21-3f6ed95047db)

![image](https://github.com/user-attachments/assets/cc542654-d9a2-4020-8165-5ccff6f072cf)

Results:

![image](https://github.com/user-attachments/assets/0cbe0b38-69a5-4e6b-858e-b781fced38fb)


## Contact

For any questions or feedback, please reach out at mahata2657@gmail.com.

---
