# SMP-prediction
## Popularity prediction for Flicker Posts using the SMP challenge dataset
### Social Media Post Popularity Prediction Framework
The proposed framework aims to predict the popularity of social media posts by leveraging multimodal information through early fusion. Feature extraction begins with Residual Nets (ResNet) for image features and text features obtained using Global Vectors for Word Representation (GloVe) embeddings combined with a bi-directional Long Short-Term Memory (LSTM) model. These extracted features are then combined using Principal Component Analysis (PCA) into a unified feature vector for predicting post popularity.

### Features:
* ResNet for Image Features: Utilizes Residual Nets for extracting rich image features.
* GloVe Embeddings and LSTM: Employs GloVe embeddings and a bi-directional LSTM model for extracting text features.
* Early Fusion with PCA: Combines the extracted image and text features early in the feature extraction process using Principal Component Analysis (PCA) for effective feature representation.
* Dataset: SMPD (Social Media Prediction Dataset)
* Description: Contains 486K social multimedia posts from 70K users, including anonymized photo-sharing records, user profiles, web images, text, time, location, and category information.
* Collection Source: Collected from Flickr, one of the largest photo-sharing platforms.
* Temporal Split: For time-series forecasting, training/testing data are split into chronological sets based on date and time.
### Flowchart: 

![image](https://github.com/A5hw1nneg1/SMP-prediction/assets/96017158/dc7b114c-ae76-4094-9a06-454f4f911036)

### Experimental Results:
Experimental results demonstrate the effectiveness of this early fusion approach on the SMPD dataset. The framework exhibits promising performance in predicting the popularity of social media posts, showcasing its potential for practical applications.


