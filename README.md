# IMPLEMENTATION OF PLANT DISEASE CLASSIFICATION USING IMAGE PROCESSING
  A CASE STUDY USING TOMATO LEAVES

## EXECUTIVE SUMMARY
### Introduction:
Plant diseases are a major hindrance in Agriculture, causing significant crop losses as well as negatively impacting human health. Early disease detection is crucial for minimizing these losses and ensuring food security. Traditional methods of disease detection are time-consuming, prone to errors, and impractical for large-scale farms. This study will focus on implementing machine learning models to automate disease classification using image processing. Tomato leaves will be used as the case study. The significance of this research lies in its potential to enhance crop yields, farmer income, and food security by providing a reliable tool for early disease detection.

### Methodology:
The study used an experimental design. Both classical machine learning and deep learning models were implemented and compared on a dataset of tomato leaf images from Kaggle. An algorithm for detecting tomato diseases was proposed, focusing on image segmentation and classification. Limitations in dataset quality and generalizability were acknowledged.

### Results:
SVC Achieved 92% accuracy, excelling in distinguishing healthy leaves and certain diseases, but faced issues with diseases having similar symptoms. KNN Recorded 87% accuracy with high precision and recall, but struggled with diseases having overlapping symptoms. Logistic Regression Obtained 83% accuracy, showing strong precision and recall but lower accuracy compared to other models. Random Forest Achieved 90% accuracy, performing well overall but facing challenges with diseases having similar symptoms. Decision Tree showed 88% accuracy and high precision and recall, though the absence of an F1-score makes its full performance assessment difficult.

### Conclusion:
KNN and Logistic Regression are recommended for balanced performance with high Precision and Recall, and the highest F1-scores. SVC is suitable when Accuracy and Specificity are prioritized. Random Forest is a robust choice for high Precision, Recall, and F1-Score, despite a slightly lower Accuracy. Decision Tree may be considered f interpretability is critical, but its lower Accuracy and missing F1-score should be noted.


