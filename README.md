🥔 Potato Defect Detection Dataset
📌 Overview

The Potato Defect Detection Dataset is designed for research and development in computer vision and deep learning-based classification of potato slice quality. The dataset contains processed images categorized into defected and healthy potato slices. It is suitable for image classification, defect detection, and machine learning experiments.

📊 Dataset Details

Total Images: 2015

Classes:

Defected Potato Slices: 896 images

Healthy Potato Slices: 1119 images

🖼️ Image Preprocessing

All images were standardized to ensure consistency and optimal performance for deep learning models:

Image Resolution: 224 × 224 pixels

Color Format: RGB

Compression Format: JPEG

File Size: < 0.5 MB per image

Image Density: 72 DPI

These preprocessing steps help maintain storage efficiency while preserving essential visual features.

🔄 Data Augmentation

To improve model robustness and variability, stochastic augmentation techniques were applied:

Rotation: up to ±25°

Width/Height Translation: up to 8%

Zoom: up to 15%

Shear Transformation: up to 15%

Horizontal Flipping

Augmentation was performed in a class-consistent manner to maintain label integrity.
