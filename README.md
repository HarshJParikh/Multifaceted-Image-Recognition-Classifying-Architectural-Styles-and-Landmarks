
# Architectural Style and Landmark Recognition

In this repository, we present a comprehensive approach to classifying images based on their architectural styles and landmarks using the VGG16 model, transfer learning, and data augmentation techniques.

## Table of Contents
1. [Introduction](#introduction)
2. [Data Description](#data-description)
3. [Methodology](#methodology)
4. [Results](#results)
5. [Dependencies](#dependencies)
6. [Getting Started](#getting-started)
7. [Skills and Tech Stack](#skills-and-tech-stack)
8. [License](#license)
9. [Acknowledgments](#acknowledgments)

## Introduction

Recognizing architectural styles and landmarks is a challenging endeavor in the realm of computer vision, especially with limited datasets. This project focuses on addressing these challenges and classifying images into 6 distinct architectural styles and 30 specific landmarks.

## Data Description

The dataset comprises images from:
- 6 architectural styles: Gothic, Modern, Mughal, Neoclassical, Pagodas, and Pyramids.
- 30 landmarks, with 5 landmarks per style.
- Each landmark consists of 14 images, underscoring the challenge of working with a limited dataset.

## Methodology

1. **Transfer Learning with VGG16:** The pre-trained VGG16 model was fine-tuned by adjusting specific layers for adaptability to our classification tasks.
2. **Data Augmentation:** Techniques such as rotation, width and height shift, zoom, and horizontal flipping were employed to artificially expand the dataset.
3. **Multi-output Model Strategy:** Designed a two-branch model – one for category (style) classification and another for landmark identification.

## Results

- **Category Classification:** Achieved an F1 score of 0.9640 and a recall score of 0.9642.
- **Landmark Classification:** Secured an F1 score of 0.8638 and a recall score of 0.8690.

## Dependencies

- Python 3.x
- Keras
- Pandas
- Matplotlib
- Seaborn
- PIL
- Sklearn

## Skills and Tech Stack

1. Programming & Scripting: Python
2. Data Manipulation: Pandas
3. Image Processing: PIL (Python Imaging Library)
4. Deep Learning Framework: Keras
5. Pre-trained Model & Transfer Learning: VGG16
6. Data Visualization: Matplotlib, Seaborn
7. Machine Learning Tools: Scikit-learn
8. Data Augmentation: ImageDataGenerator from Keras
9. Model Regularization: Dropout, Batch Normalization
10. Model Evaluation: Classification metrics (F1 score, Recall)
11. Version Control: Git

## License

This project is licensed under the MIT License. Check the [LICENSE.md](LICENSE.md) file for more details (if available).

## Acknowledgments

- Heartfelt gratitude to the DSCI552 course team for the guidance.
- Team members and contributors for their relentless efforts and insights.
