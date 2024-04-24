# Obesity Risk Prediction

## About
This is a Mini-Project for SC1015 (Introduction to Data Science and Artificial Intelligence) course which aims to explores the obesity risk among individuals by examining various health metrics and daily habits. Utilizing the Multi-Class Prediction of Obesity Risk Dataset, we apply machine learning techniques to predict and classify obesity levels, providing insights into the significant factors that contribute to obesity.
### Project Structure
- `README.md`: Provides an overview of the project, dataset, and instructions for setup.
- [Dataset](https://github.com/neyvivu/SC1015PROJ_FDAC_Group6/tree/main/Dataset): Dataset file utilized for the analysis, including the [original dataset](https://github.com/neyvivu/SC1015PROJ_FDAC_Group6/blob/main/Dataset/train.csv) and modified datasets served as resources for each step.
- [Data Preparation](https://github.com/neyvivu/SC1015PROJ_FDAC_Group6/blob/main/Data-Preparation.ipynb) 
- [Data Visualization](https://github.com/neyvivu/SC1015PROJ_FDAC_Group6/blob/main/Data-Visualization.ipynb)
- [Data Resampling and Splitting](https://github.com/neyvivu/SC1015PROJ_FDAC_Group6/blob/main/Data-Resampling-and-Splitting.ipynb)
- [Random Forest Classifier](https://github.com/neyvivu/SC1015PROJ_FDAC_Group6/blob/main/%20Random%20Forest%20Classifier.ipynb)
- [XGBoost](https://github.com/neyvivu/SC1015PROJ_FDAC_Group6/blob/main/XGBoost.ipynb)
### Contributors
- [@neyvivu](https://github.com/neyvivu) - Vu Thao Nguyen: Data Preparation (Data Cleaning), Data Extraction, Data Visualization
- [@Lamnu1902](https://github.com/Lamnu1902) - Nguyen Tung Lam: Data Resampling, Random Forest Classifier, XGBoost
  
## Dataset
The analysis utilizes data from the [Multi-Class Prediction of Obesity Risk Dataset](https://www.kaggle.com/competitions/playground-series-s4e2) available on Kaggle. This dataset includes comprehensive information about individuals' eating habits, physical activity, and other relevant health metrics. Note: Due to the terms of use on Kaggle, please download the original dataset directly from the provided link. 

## Problem Definition
Our project seeks to answer the following questions:
- Which variables are most predictive of an individual’s obesity risk?
- Can we effectively classify individuals into different categories of obesity based on their lifestyle and health data?

## Model Used
1. Random Forest Classifier
2. XGBoost

## Installation
First, ensure you have Python installed on your system. Follow these steps to set up the project environment:

```bash
# Clone the repository
git clone <repository-url>
cd <repository-folder>

# Install required Python packages
pip install -r requirements.txt
```

## Conclusion

- **Predictive Variables**: Key variables such as dietary habits, physical activity levels, and routine health monitoring were found to have a significant impact on obesity risk. These findings emphasize the importance of lifestyle factors in predicting obesity.
- **Model Performance**: The Random Forest Classifier and XGBoost models were instrumental in tackling the predictive challenges posed by the dataset. Both models efficiently handled the non-linear relationships between variables and outcomes.
- **Effectiveness of Ensemble Methods**: Both Random Forest and XGBoost, leveraging ensemble learning techniques, demonstrated strong predictive performance. The Random Forest model excelled in handling the complexity of the dataset, while XGBoost provided a robust approach to improve precision and recall.
- **Handling Class Imbalance**: The use of advanced resampling techniques significantly improved the predictive accuracy on minority classes, showing the effectiveness of these methods in real-world data scenarios.
- **Feasibility of Prediction**: Our analysis confirms the feasibility of using machine learning to categorize levels of obesity with a high degree of accuracy and recall, thus demonstrating the practical applications of these models in health assessments.

### What Did We Learn from This Project?
- **Advanced Machine Learning Techniques**: Gained hands-on experience with sophisticated machine learning algorithms like Random Forest and XGBoost. We explored their parameters, learning how to tune them for optimal performance.
- **Data Resampling Strategies**: Improved our approach to dealing with imbalanced datasets, employing techniques such as SMOTE (Synthetic Minority Over-sampling Technique) to enhance model training outcomes.
- **Practical Data Science Applications**: Enhanced our understanding of how data science can be applied in healthcare to predict complex outcomes such as obesity levels.
- **Collaborative Skills**: Developed stronger collaborative skills by using GitHub for version control and project management, facilitating effective teamwork across different aspects of the project.
- **Statistical Metrics Mastery**: Deepened knowledge of critical evaluation metrics like accuracy, precision, recall, and F1 score, essential for assessing model performance in medical research.

This project not only expanded our technical capabilities but also provided valuable insights into the factors influencing obesity, showcasing the potential of data science to inform public health strategies.

### References
- https://www.kaggle.com/competitions/playground-series-s4e2
- https://www.youtube.com/watch?si=tCa5kLpL8RsDoH8C&v=v6VJ2RO66Ag&feature=youtu.be
- https://www.youtube.com/watch?si=57QwNp3Z-iouAkbh&v=_QuGM_FW9eo&feature=youtu.be
- https://www.analyticsvidhya.com/blog/2018/09/an-end-to-end-guide-to-understand-the-math-behind-xgboost/?fbclid=IwAR18V_OM_9wUbHpStqwc4kWk9M0xzal1li28NlW-FlAISRQXaFInds2-y58
