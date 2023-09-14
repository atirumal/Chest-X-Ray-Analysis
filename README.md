# Chest X-Ray Analysis Model

This project is an ML model that can diagnose various lung diseases/conditions when provided with images of chest X-rays. It uses TensorFlow, Pandas, and Scikit-learn to perform image analysis, data preprocessing, and machine learning to accurately classify and identify potential health issues in chest X-ray images at ~95% accuracy. 

The data for training was sourced from the NIH CXR8 dataset, a comprehensive dataset provided by the U.S. Department of Health & Human Services containing labelled chest X-ray images of over 30,000 patients. 

To assess the performance of the model in various use cases, I generated an ROC curve which provides a comprehensive view of the model's performance across different decision thresholds. Depending on the specific use case, you may want to prioritize sensitivity (identifying as many lung diseases as possible) or specificity (avoiding false alarms). The ROC curve helps you choose an appropriate threshold that aligns with your priorities. You can then change this cutoff value using the slider and regenerate the code.
