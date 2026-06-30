# PRODIGY_ML_05
# Food Recognition & Calorie Estimation

## Overview
A deep learning model to recognize food items from images and estimate their calorie content using Transfer Learning (MobileNetV2).

## Dataset
Food-101-Tiny - 1500 images across 10 food categories

## Food Categories
Apple Pie, Bibimbap, Cannoli, Edamame, Falafel, French Toast, Ice Cream, Ramen, Sushi, Tiramisu

## Approach
- Initial approach: SVM with HOG + Color features (33.33% accuracy)
- Final approach: CNN with MobileNetV2 Transfer Learning (71% accuracy)
- Calorie lookup table mapped to each food category

## Results
- Final Accuracy: 71%
- Significant improvement using deep learning over classical ML

## Libraries Used
- TensorFlow, Keras, OpenCV, scikit-learn, MobileNetV2
