# Celebal Technologies Data Science Internship — Weekly Assignments (2026)

This repository contains my weekly assignment submissions completed as part of the Celebal Technologies Data Science Internship Program.

## Assignment Progress

| Week | Topic | Status |
|------|-------|--------|
| Week 1 | Python, NumPy, Linear Algebra, Statistics, Probability & ML Foundations | Completed |
| Week 2 | Tesla Deliveries Forecasting and Time Series Analysis | Completed |
| Week 3 | Customer Intelligence System using K-Means & DBSCAN Clustering | Completed |
| Week 4 | Image Classification on CIFAR-10 using ANN & CNN | Completed |
| Week 5 | Text Generation using RNN, LSTM & GRU | Completed |
| Week 6 | Autoencoder for Image Denoising (MNIST) | Completed |

## Topics Covered in Week 1

* NumPy Arrays and Matrix Operations
* Vector Norms and Linear Algebra
* Eigenvalues and Eigenvectors
* Singular Value Decomposition (SVD)
* Statistical Analysis and Hypothesis Testing
* Probability Distributions
* Bayes' Theorem and Naive Bayes
* Population Stability Index (PSI)
* Central Limit Theorem (CLT)
* Data Visualization using Matplotlib

## Tools Used

* Python
* NumPy
* Pandas
* SciPy
* Matplotlib
* Google Colab

## Key Learnings



Through this assignment, I gained practical experience with NumPy operations, matrix transformations, eigenvalues and eigenvectors, probability distributions, Bayes' theorem, and the Central Limit Theorem. I also learned how data visualization helps interpret mathematical and statistical concepts.

## Assignment Highlights

- Implemented linear algebra concepts using NumPy

- Visualized statistical distributions using Matplotlib

- Applied Bayes' theorem for spam classification

- Explored Population Stability Index (PSI) for data drift detection

- Demonstrated the Central Limit Theorem through simulation


# Week 2 – Tesla Deliveries Forecasting and Time Series Analysis

## Overview

This assignment focuses on exploratory data analysis, feature engineering, machine learning, and basic time series analysis using Tesla delivery and production data from 2015–2025.

## Objectives

* Analyze Tesla production and delivery trends.
* Perform data cleaning and preprocessing.
* Create meaningful visualizations for business insights.
* Engineer features for forecasting.
* Build and evaluate machine learning models.
* Compare Linear Regression and Random Forest performance.
* Conduct a stationarity test using the Augmented Dickey-Fuller (ADF) test.

### Assignment Highlights

* Performed Exploratory Data Analysis (EDA) on Tesla production and delivery data from 2015–2025.
* Analyzed delivery trends across different vehicle models and regions.
* Investigated relationships between production units and estimated deliveries using correlation analysis.
* Created lag and rolling mean features to capture historical delivery patterns.
* Built and evaluated a Linear Regression model for delivery forecasting.
* Applied 5-Fold Cross Validation to assess model stability and generalization.
* Tuned a Random Forest Regressor using GridSearchCV.
* Compared model performance using MAE, RMSE, and R² Score.
* Identified the most influential features through feature importance analysis.
* Conducted an Augmented Dickey-Fuller (ADF) test to evaluate time-series stationarity.
* Generated forecasts and compared predicted values against actual deliveries.

## Dataset

**Tesla Deliveries and Production Dataset (2015–2025)**

The dataset contains information related to Tesla vehicle production, deliveries, models, regions, and other factors that influence demand and supply patterns over time.

## Tasks Performed

* Dataset inspection and quality checks
* Missing value and duplicate analysis
* Exploratory Data Analysis (EDA)
* Correlation analysis
* Feature engineering (Label Encoding, Lag Features, Rolling Mean)
* Linear Regression model training
* Cross-validation
* Random Forest with GridSearchCV
* Feature importance analysis
* ADF stationarity testing
* Forecast generation and model comparison

## Key Learnings

* Understanding time-series oriented train-test splitting
* Importance of feature engineering in forecasting
* Model evaluation using MAE, RMSE, and R² Score
* Comparing linear and ensemble machine learning models
* Interpreting stationarity in time series data

## Files Included

* `week2_ArpitaDas.ipynb` – Week 2 assignment notebook
* `tesla_deliveries_dataset_2015_2025.csv` – Dataset used for analysis

## Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn
* Statsmodels
* Jupyter Notebook


# Week 3 – Customer Intelligence System using Clustering

## Overview

This assignment focuses on unsupervised learning techniques to build a Customer Intelligence / Country Segmentation system using socio-economic and health indicators.

The objective is to identify meaningful country groups, compare clustering approaches, and derive actionable insights from the discovered segments.

## Objectives

- Clean and preprocess country-level socio-economic data.
- Standardize features for clustering.
- Determine the optimal number of clusters using the Elbow Method.
- Build and evaluate a K-Means clustering model.
- Compare results with DBSCAN.
- Visualize clusters using PCA.
- Interpret socio-economic patterns across clusters.

### Assignment Highlights

- Performed data cleaning, missing value handling, and duplicate removal.
- Applied StandardScaler for feature normalization.
- Used the Elbow Method to determine the optimal number of clusters.
- Built a K-Means clustering model with three clusters.
- Evaluated clustering performance using the Silhouette Score.
- Implemented DBSCAN for comparative clustering analysis.
- Reduced data dimensions using PCA for visualization.
- Identified economically developed, developing, and high-risk country groups through cluster interpretation.

## Dataset

**Country Socio-Economic & Health Indicators Dataset**

The dataset contains country-level indicators such as income, health expenditure, child mortality, exports, imports, inflation, life expectancy, and other socio-economic metrics used for clustering and segmentation.

## Tasks Performed

- Dataset inspection and preprocessing
- Missing value imputation
- Duplicate record removal
- Feature scaling using StandardScaler
- Elbow Method analysis
- K-Means clustering
- Silhouette Score evaluation
- DBSCAN clustering
- PCA-based visualization
- Cluster interpretation and socio-economic insights

## Key Learnings

- Understanding the workflow of unsupervised learning.
- Selecting the optimal number of clusters using the Elbow Method.
- Evaluating clustering quality with the Silhouette Score.
- Comparing centroid-based and density-based clustering algorithms.
- Applying PCA for dimensionality reduction and visualization.
- Interpreting clusters to derive meaningful socio-economic insights.

## Files Included

- `week3_ArpitaDas.ipynb` – Week 3 assignment notebook
- `country_data.csv` – Dataset used for clustering and segmentation

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

# Week 4 – Image Classification on CIFAR-10 using ANN & CNN

## Overview

This assignment focuses on image classification using the CIFAR-10 dataset by implementing both an Artificial Neural Network (ANN) and a Convolutional Neural Network (CNN). The objective is to compare their performance, analyze training strategies, and evaluate the effectiveness of deep learning architectures for image recognition.

## Objectives

- Load and preprocess the CIFAR-10 dataset.
- Build an Artificial Neural Network (ANN) for image classification.
- Build a Convolutional Neural Network (CNN).
- Train and evaluate both models.
- Compare ANN and CNN performance.
- Analyze training and validation accuracy/loss.
- Evaluate models using classification metrics.

## Assignment Highlights

- Loaded and preprocessed the CIFAR-10 dataset.
- Normalized image pixel values for faster convergence.
- Implemented an ANN using fully connected Dense layers.
- Built a CNN using convolutional and max-pooling layers.
- Applied Dropout to reduce overfitting.
- Trained both models using the Adam optimizer.
- Compared training and validation performance of ANN and CNN.
- Evaluated models on the test dataset.
- Generated confusion matrix and classification report.
- Demonstrated the effectiveness of CNNs for image classification tasks.

## Dataset

**CIFAR-10 Dataset**

The CIFAR-10 dataset consists of 60,000 color images (32×32 pixels) across 10 object categories:

- Airplane
- Automobile
- Bird
- Cat
- Deer
- Dog
- Frog
- Horse
- Ship
- Truck

### Dataset Split

- Training Images: 50,000
- Testing Images: 10,000

## Tasks Performed

- Dataset loading and exploration
- Data preprocessing and normalization
- Label encoding
- ANN model development
- CNN model development
- Model compilation and training
- Accuracy and loss visualization
- Performance evaluation
- Confusion Matrix generation
- Classification Report generation
- ANN vs CNN comparison

## Key Learnings

- Understanding image preprocessing techniques for deep learning.
- Learning the differences between ANN and CNN architectures.
- Understanding feature extraction through convolutional layers.
- Applying Dropout to improve model generalization.
- Evaluating classification models using Accuracy, Precision, Recall, and F1-Score.
- Comparing deep learning approaches for image recognition problems.

## Files Included

- `week4_ArpitaDas.ipynb` – Week 4 assignment notebook
- `README.md`

## Technologies Used

- Python
- TensorFlow
- Keras
- NumPy
- Matplotlib
- Scikit-learn
- Google Colab

# Week 5 – Text Generation using RNN, LSTM & GRU

## Overview

This assignment focuses on Natural Language Processing (NLP) using Recurrent Neural Networks (RNNs). The objective is to build and compare Simple RNN, LSTM, and GRU models for next-word prediction and text generation using a custom text corpus.

## Objectives

- Build a text generation pipeline using TensorFlow/Keras.
- Tokenize and preprocess a custom text corpus.
- Generate input sequences for next-word prediction.
- Implement and compare Simple RNN, LSTM, and GRU models.
- Train each model and compare their learning performance.
- Visualize training loss across all models.
- Generate text using trained sequence models.

### Assignment Highlights

- Created a custom text corpus for language modeling.
- Tokenized text and generated n-gram input sequences.
- Applied sequence padding and one-hot encoding for model training.
- Implemented a Simple RNN model for next-word prediction.
- Built LSTM and GRU models for comparison.
- Increased embedding dimensions and hidden units for improved learning.
- Trained all models for 200 epochs.
- Compared model performance using training loss curves.
- Generated 10-word text sequences from a given seed text.
- Evaluated the strengths of RNN, LSTM, and GRU architectures.

## Dataset

**Custom Text Corpus**

A self-created text corpus was used to train the language models for next-word prediction and text generation. The corpus was tokenized and transformed into sequential training samples.

## Tasks Performed

- Text preprocessing and cleaning
- Tokenization using Keras Tokenizer
- Sequence generation and padding
- One-hot encoding of target labels
- Simple RNN implementation
- LSTM implementation
- GRU implementation
- Model training and evaluation
- Training loss visualization
- Text generation using trained models

## Key Learnings

- Understanding sequence modeling for Natural Language Processing.
- Learning the differences between Simple RNN, LSTM, and GRU architectures.
- Preparing text data for deep learning models.
- Implementing next-word prediction using recurrent neural networks.
- Comparing model learning behavior using training loss.
- Generating coherent text from trained language models.

## Files Included

- `week5_ArpitaDas.ipynb` – Week 5 assignment notebook
- `README.md`

## Technologies Used

- Python
- TensorFlow
- Keras
- NumPy
- Matplotlib
- Google Colab

# Week 6 – Autoencoder for Image Denoising (MNIST)

## Overview

This assignment focuses on unsupervised deep learning using autoencoders. The objective is to build and train a Denoising Autoencoder that learns to remove artificial noise from MNIST handwritten digit images while preserving their underlying structure.

## Objectives

- Load and preprocess the MNIST dataset.
- Introduce artificial noise to create noisy input images.
- Build a Convolutional Autoencoder (encoder-decoder architecture).
- Train the model using noisy images as input and clean images as targets.
- Generate denoised outputs on the test set.
- Evaluate denoising performance visually and quantitatively.

### Assignment Highlights

- Loaded MNIST digit images from the provided dataset and normalized pixel values.
- Added Gaussian noise to training and test images to simulate corrupted input.
- Built a Convolutional Autoencoder using Conv2D, MaxPooling2D (encoder), and Conv2D, UpSampling2D (decoder) layers.
- Trained the autoencoder using noisy images as input and clean images as reconstruction targets.
- Used Adam optimizer, binary crossentropy loss, and EarlyStopping to prevent overfitting.
- Visualized training and validation loss curves across epochs.
- Generated denoised reconstructions on the test set.
- Compared original, noisy, and denoised images side by side.
- Evaluated reconstruction quality using PSNR (Peak Signal-to-Noise Ratio) as an additional metric.

## Dataset

**MNIST Handwritten Digits Dataset**

The dataset consists of 60,000 training images and 10,000 test images of handwritten digits (0–9), each of size 28×28 pixels in grayscale.

## Tasks Performed

- Dataset loading and preprocessing
- Normalization and reshaping for CNN input
- Artificial noise generation (Gaussian noise)
- Convolutional Autoencoder architecture design
- Model training with EarlyStopping
- Training/validation loss visualization
- Denoised image generation on test set
- Original vs Noisy vs Denoised result comparison
- PSNR-based quantitative evaluation

## Key Learnings

- Understanding the encoder-decoder structure of autoencoders.
- Learning how compressed (bottleneck) representations retain key image information.
- Applying autoencoders specifically for denoising tasks, not just reconstruction.
- Understanding the role of loss functions (binary crossentropy) in image reconstruction.
- Using PSNR as a quantitative metric to evaluate image restoration quality.
- Recognizing tradeoffs in reconstruction sharpness with different loss functions.

## Files Included

- `week6_ArpitaDas.ipynb` – Week 6 assignment notebook

## Technologies Used

- Python
- TensorFlow
- Keras
- NumPy
- Matplotlib
- Scikit-image (for PSNR metric)
- Google Colab

## Author

Arpita Das

B.Tech Computer Science & Engineering
