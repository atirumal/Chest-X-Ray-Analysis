# Chest X-Ray Analysis Model

This project is an ML model that can diagnose various lung diseases/conditions when provided with images of chest X-rays. It uses TensorFlow, Pandas, and Scikit-learn to perform image analysis, data preprocessing, and machine learning to accurately classify and identify potential health issues in chest X-ray images at ~95% accuracy. 

The data for training was sourced from the NIH CXR8 dataset, a comprehensive dataset provided by the U.S. Department of Health & Human Services containing labelled chest X-ray images of over 30,000 patients. 

To assess the performance of the model in various use cases, I generated an ROC curve which provides a comprehensive view of the model's performance across different decision thresholds. Depending on the specific use case, you may want to prioritize sensitivity (identifying as many lung diseases as possible) or specificity (avoiding false alarms). The ROC curve helps you choose an appropriate threshold that aligns with your priorities. You can then change this cutoff value using the slider and regenerate the code.

Model diagnosing Cardiomegaly:
<img width="582" alt="Screenshot 2023-09-14 at 2 52 04 PM" src="https://github.com/atirumal/Chest-X-Ray-Analysis/assets/78452887/ccc6482d-ada3-46c2-935d-151ccad6c91a">
<img width="561" alt="Screenshot 2023-09-14 at 2 52 23 PM" src="https://github.com/atirumal/Chest-X-Ray-Analysis/assets/78452887/39350f65-1b93-4c28-85b8-2c0c0e73cc47">
<img width="560" alt="Screenshot 2023-09-14 at 2 52 38 PM" src="https://github.com/atirumal/Chest-X-Ray-Analysis/assets/78452887/bbd7c9e4-b241-49de-964f-f48495dee3cf">
