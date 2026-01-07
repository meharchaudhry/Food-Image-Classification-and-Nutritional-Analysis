# Food-Image-Classification-and-Nutritional-Analysis

# Food Image Classification & Nutrition Analysis (EfficientNet & ResNet)

This project builds a deep learning–based food image classification system using modern convolutional neural networks to automatically identify food items from images and support nutrition-related insights. The system is designed for real-world robustness and scalability.

## Problem Statement
Manual food tracking is time-consuming and inaccurate. The goal of this project is to classify food images reliably and map predictions to nutritional information to assist health-conscious users and travelers.

## Approach
- Trained and evaluated **EfficientNet (B3/B4)** and **ResNet-50** models using **transfer learning** for multi-class food classification.
- Fine-tuned pretrained models on the **Food-101 dataset**, adapting final classification layers for 100+ food categories.
- Applied **data augmentation, regularization, and learning rate scheduling** to improve generalization and reduce overfitting.
- Compared model performance across architectures to evaluate accuracy–efficiency trade-offs.
- Extended predictions by linking classified food items to **calorie and macronutrient estimates** using a structured nutrition dataset.

## Tools & Technologies
- Python, PyTorch
- EfficientNet (B3/B4), ResNet-50
- Food-101 Dataset
- NumPy, Pandas, Matplotlib

## Results
- Achieved **high classification accuracy (~94%)** on Food-101.
- EfficientNet models delivered **strong accuracy with fewer parameters**, making them suitable for deployment on resource-constrained systems.
- Project selected as **Best Project** at FLAME University’s Machine Learning Fair.

## Use Case
Can be integrated into mobile or web applications for food logging, nutrition tracking, and health analytics, enabling real-time food recognition.

## Future Improvements
- Add portion-size estimation for more accurate nutrition predictions.
- Extend to mixed-dish and multi-label classification.
- Deploy as a lightweight inference API or mobile-ready model.
