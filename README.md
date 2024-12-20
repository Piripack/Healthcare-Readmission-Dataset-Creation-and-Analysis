# Healthcare Readmission Dataset Creation and Analysis

## Objective
The goal of this project was to **create a realistic healthcare dataset** to predict **patient readmissions** within 30 days. The dataset includes key features like **age**, **chronic conditions**, **previous readmissions**, **treatment costs**, and **days between discharge and readmission**. The focus was on making the dataset **valuable for machine learning models**, ensuring data quality, and addressing common real-world data issues.

---

## Steps Taken

### 1. **Data Creation**
- Generated a **synthetic dataset** representing patients, including important attributes such as **age**, **chronic conditions**, **previous readmissions**, **costs**, and **days between discharge and readmission**.
  
### 2. **Data Cleaning & Transformation**
- Handled missing values, **negative costs**, and unrealistic **age distributions** to simulate a realistic healthcare environment.
- Adjusted the **age distribution** to focus on a **realistic healthcare population**, ensuring older patients were more prominently represented, given their higher readmission risk.

### 3. **Noise Introduction**
- Introduced **24% noise** to the dataset, simulating real-world issues like data entry mistakes or unexpected patterns, testing the model’s ability to handle imperfect data.

### 4. **Exploratory Data Analysis**
- Visualized key features such as **age**, **cost**, and **chronic conditions** to uncover patterns and ensure the dataset mimics real-world healthcare scenarios.
  
### 5. **Model Development**
- Built a **Random Forest model** to predict **readmissions**, evaluating its performance using metrics like **accuracy**, **precision**, **recall**, **ROC AUC**, and **AUC-PR**.

### 6. **Final Dataset**
- The final dataset was designed to reflect **realistic healthcare distributions** and tested for effectiveness with **predictive modeling**.

---

## Results

- **Age Distribution**: Adjusted to focus on **older patients (50+ years)**, who are more likely to be readmitted, while reducing overrepresentation of younger age groups (18-20).
  
- **Model Performance**:
  - **Accuracy**: 60-67%
  - **Precision**: 64-68%
  - **Recall**: 69-77%
  
- **Feature Importances**: The most important features for predicting readmission were found to be **age**, **previous readmissions**, and **cost**.

---

## Key Takeaways

- **Realistic Data Generation**: Building a **valuable healthcare dataset** requires balancing **realism** and **noise** while ensuring data quality.
- **Predictive Features**: **Age**, **previous readmissions**, and **cost** are highly predictive of readmission risk.
- **Data Cleaning & Feature Engineering**: These steps were critical in improving model performance and ensuring the dataset was valuable for real-world applications.

---

## Conclusion

This project demonstrates the importance of creating high-quality, **realistic healthcare datasets** for **predictive modeling**. By addressing common data challenges and enhancing the dataset's structure, it became a valuable resource for testing and developing **machine learning models** for **readmission prediction**.

---

## License
This project is licensed under the **MIT License**.

---

## Contributions
Feel free to contribute or fork the repository to improve the dataset and model.
