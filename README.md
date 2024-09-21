# Instagram Likes Prediction Using Deep Learning and Traditional Models

## Project Overview
This project aims to predict Instagram image likes categorized as **low**, **medium**, or **high**. We use a combination of **deep learning** and **traditional machine learning** models to analyze and predict engagement based on image and textual metadata (comments, followers, and posting time). The dataset includes 3,785 Instagram images and corresponding features.

## Models Explored
1. **Convolutional Neural Network (CNN)**: A deep learning model that uses only image data to predict like categories.
2. **CLIP (Contrastive Language-Image Pretraining)**: Combines image embeddings with log-transformed textual features for accurate predictions.
3. **Random Forest**: A traditional ensemble learning method using only numerical features.
4. **Logistic Regression**: A simple, interpretable classification model applied to numerical features.
5. **XGBoost**: A powerful, efficient gradient-boosted decision tree algorithm.

## Key Results
- **XGBoost** achieved the highest accuracy at **83.36%**, closely followed by **CLIP** at **83.22%**.
- **Random Forest** performed well with an accuracy of **82.96%**.
- **Logistic Regression** had a lower accuracy of **76.35%**.
- **CNN**, using only image data, had the lowest accuracy at **50.46%**, indicating the importance of combining image and textual features for this task.

## Next Steps
To improve model performance and ensure fair comparison, further exploration includes:
- **Hyperparameter tuning** and **cross-validation** across all models to optimize their configurations and ensure robustness.

## Dataset
The dataset includes:
- **Images**: 3,785 Instagram posts.
- **Numerical Features**: Number of comments, followers, and posting time.
- **Target**: Categorizing Instagram likes into low, medium, and high classes based on Z-scores.

## Installation and Setup
To reproduce this project, follow these steps:

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/instagram-likes-prediction.git
   cd instagram-likes-prediction
