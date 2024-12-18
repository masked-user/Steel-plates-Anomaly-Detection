# Steel Plate Anomaly Detection

## **Introduction**
Steel plate anomaly detection is a critical process in quality control within manufacturing industries. Identifying defects or anomalies in steel plates ensures that substandard products do not proceed further in the production line, maintaining both safety and efficiency. This project focuses on leveraging data-driven approaches to detect anomalies in steel plates based on various features, such as length, width, and defect type.

By analyzing the dataset, the goal is to classify steel plates as defective or non-defective and to understand the characteristics of different types of anomalies. This project demonstrates the use of statistical techniques and machine learning models to improve anomaly detection processes, contributing to enhanced operational efficiency and reduced production waste.

---

## **Research Questions**
1. **Defect Identification**
   - What are the key features that distinguish defective steel plates from non-defective ones?

2. **Anomaly Classification**
   - Can the anomalies be classified into distinct types using available data?

3. **Feature Importance**
   - Which features have the most significant impact on determining whether a steel plate is defective?

4. **Model Accuracy**
   - How accurate are the predictive models in identifying anomalies, and how can they be improved?

---

## **Methods Used**

### **Dataset**
The dataset includes measurements and attributes of steel plates, such as:
- Length and width
- Material properties
- Defect types (e.g., scratches, dents)

This dataset is suitable for exploring relationships between features and identifying patterns associated with anomalies.

### **Analysis Techniques**
1. **Data Preprocessing**
   - Handled missing values, standardized measurements, and prepared the dataset for analysis.

2. **Exploratory Data Analysis (EDA)**
   - Visualized distributions and relationships to gain insights into the data.

3. **Feature Selection**
   - Applied techniques such as correlation analysis and PCA to identify the most relevant features.

4. **Machine Learning Models**
   - Implemented classification models, including decision trees, random forests, and support vector machines (SVM), to detect anomalies.

5. **Evaluation Metrics**
   - Assessed model performance using metrics such as accuracy, precision, recall, and F1-score.

---

## **Conclusion**

The project provided several key findings:
1. **Key Features**
   - Certain material properties and measurements, such as thickness and surface area, were highly correlated with defect presence.

2. **Classification Models**
   - Random forest models showed the best performance in anomaly detection, with a high F1-score and robust classification capabilities.

3. **Operational Insights**
   - Identifying critical features can help manufacturing lines implement targeted quality checks, reducing defect rates and improving efficiency.

4. **Areas for Improvement**
   - Further work is needed to address class imbalance in the dataset and improve model generalization.

---

## **Future Directions**
1. **Advanced Modeling**
   - Explore deep learning approaches, such as convolutional neural networks (CNNs), for image-based anomaly detection.

2. **Real-Time Detection**
   - Integrate models into real-time manufacturing processes for immediate anomaly detection and intervention.

3. **Root Cause Analysis**
   - Investigate the underlying causes of defects to mitigate their occurrence in the production process.

4. **Data Augmentation**
   - Use synthetic data generation techniques to address class imbalances and improve model robustness.

This project highlights the importance of data-driven solutions in enhancing quality control processes and minimizing defects in steel plate manufacturing.

