# ML-Project-Diabetes_Prediction
Here’s a well-structured and detailed description of the diabetes prediction project using machine learning:  

---

**Diabetes Prediction Using Machine Learning**  

This project focuses on predicting diabetes using a machine learning model trained on a structured dataset. The dataset used for this study is a CSV file containing **768 rows and 9 columns**, where the features include various health parameters such as glucose level, blood pressure, BMI, and other relevant factors.  

### **Technologies and Libraries Used**  
- **NumPy & Pandas**: Used for data manipulation and analysis.  
- **Scikit-learn (sklearn)**: Utilized for data preprocessing, model selection, and performance evaluation.  

### **Data Preprocessing**  
- **Standardization**: The dataset exhibited an uneven distribution of feature values. To address this, the **StandardScaler** from (sklearn.preprocessing) was applied to normalize the feature values, ensuring that all features contribute equally to the model's learning process.  
- **Train-Test Split**: The dataset was divided into **training and testing sets** using (train_test_split) from (sklearn.model_selection) to evaluate model performance effectively.  

### **Model Selection and Training**  
The **Support Vector Machine (SVM)** algorithm was chosen for classification, specifically the **Support Vector Classifier (SVC)** with a **linear kernel**. This algorithm is well-suited for binary classification tasks and works efficiently with high-dimensional data.  

### **Performance Evaluation**  
To assess the model's predictive capability, the **accuracy score** was calculated using (accuracy_score) from (sklearn.metrics). The results obtained are as follows:  
- **Training Accuracy**: **78.66%**  
- **Testing Accuracy**: **77.27%**  

These accuracy scores indicate that the model performs well in distinguishing between diabetic and non-diabetic individuals based on the given dataset.  

### **Conclusion**  
This project successfully demonstrates the application of machine learning in **predicting diabetes** based on medical parameters. The **SVM classifier with a linear kernel** has shown promising results, making it a viable choice for such classification tasks. Further improvements can be made by experimenting with other machine learning models, feature engineering techniques, or hyperparameter tuning to enhance prediction accuracy.  

---
