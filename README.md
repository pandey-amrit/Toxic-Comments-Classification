## Toxic Comment Classification

This repository contains a comprehensive project on toxic comment classification using both traditional machine learning methods and deep learning approaches. The project aims to detect toxicity in user-generated text comments across multiple categories, including **toxic**, **severe toxic**, **obscene**, **threat**, **insult**, and **identity hate**.

### Key Features
1. **Dataset**:
   - Includes 159,571 comments with multilabel annotations.
   - Utilized tokenization and TF-IDF transformation for feature extraction.

2. **Machine Learning Models**:
   - Multinomial Naive Bayes, Logistic Regression, and Linear SVC.
   - Achieved high accuracy, with Linear SVC as the best-performing model.

3. **Voting Classifier**:
   - Combines predictions from multiple models to improve robustness.

4. **Deep Learning with LSTM**:
   - Leverages sequential data processing and word embeddings for nuanced toxicity detection.
   - Models saved in `.h5` and `.keras` formats for compatibility and future use.

5. **Evaluation Metrics**:
   - Precision, recall, and accuracy for assessing model performance.
   - Explored correlations between toxicity categories for better interpretability.

6. **Data Handling**:
   - Addressed memory issues using Jupyter Notebook for efficient processing.
   - Incorporated sequence padding and embeddings for LSTM input compatibility.

### Results
- Linear SVC demonstrated a balance between precision and recall, excelling in high-dimensional TF-IDF feature handling.
- The LSTM model captured context effectively, aided by word embeddings and sequence padding.

### Repository Content
- **Notebook**: The main code in `.ipynb` format for step-by-step execution.
- **Dataset**: Used for training and validation (not included directly due to size constraints).
- **Pre-trained Models**: Saved in both `.h5` and `.keras` formats.
- **Report**: Detailed analysis of modeling and feature engineering [PDF].

### Conclusion
This project highlights the importance of combining feature-based learning with context-aware deep learning techniques to tackle complex challenges in content moderation. The use of both traditional and deep learning models ensures robust and reliable toxicity detection.
