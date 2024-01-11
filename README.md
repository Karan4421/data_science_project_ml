**Project Title:** Analysis of the AIBL Dataset for Early Detection and Prevention of Alzheimer’s Disease

**Abstract:**
This project utilizes the AIBL dataset, a comprehensive collection of clinical, imaging, and biomarker data from elderly individuals in Australia, to explore early detection and prevention of Alzheimer’s disease and other dementias. The dataset includes diverse information on lifestyle, medical history, and medication intake, offering insights into cognitive aging and dementia. Despite some limitations, its longitudinal design is crucial for understanding these conditions.

**Introduction:**
The project addresses the growing public health concern of cognitive decline and dementia, using the AIBL dataset to explore genetic and environmental risk factors, and to develop new diagnostic and therapeutic approaches.

**Methodology:**

Data Preparation: The dataset includes 863 instances with 32 variables. Quality control was applied to MRI, genetic, and clinical data.
Handling Imbalanced Data: Techniques like SMOTE were used to address data imbalance.
Models Used: Gaussian Naïve Bayes, Support Vector Machine (SVM), Decision Tree, Logistic Regression, and Random Forest.
Tools: Python for data cleansing, model construction, and classification. Random Forest showed promising results in categorization experiments.

**Results:**

Confusion matrices were used to assess model performance.
Random Forest outperformed other models with an accuracy of 88%, followed by SVM at 86%.
The study indicated the need for a larger dataset and potential improvements using methods like XGBoost.

**Conclusion:**
The research contributes to the early diagnosis of Alzheimer's disease using machine learning, highlighting the effectiveness of the Random Forest model and underscoring the need for further data and model optimization.
