# Dengue Prediction System

### Team Members:
- Md. Bodrul Islam (11724340217)
- Md. Fuad Khan (11724340220)

### Supervisor:
Md. Meftaul Haque Mishu  
Principal Software Engineer (Data Scientist) @ Millennium Information Solution Ltd.

---

### **Project Aim**
The **Dengue Prediction System** is a machine learning-based solution aimed at predicting whether a person is Dengue Positive (1) or Negative (0) using medical test results and demographic data. By analyzing features like NS1, IgG, IgM, age, area type, and district, the system assists in the early detection of Dengue fever, enabling timely intervention and better disease management.

---

### **Data Collection**
The dataset for this project was sourced from Kaggle:  
**[Dengue Dataset - Kaggle](https://www.kaggle.com/datasets/kawsarahmad/dengue-dataset-bangladesh/data)**

Sample Data:
| Gender | Age | NS1 | IgG | IgM | Area      | AreaType  | HouseType | District | Outcome |
|--------|-----|-----|-----|-----|-----------|-----------|-----------|----------|---------|
| Female | 45  | 0   | 0   | 0   | Mirpur    | Undeveloped | Building  | Dhaka    | 0       |
| Male   | 17  | 0   | 0   | 1   | Chawkbazar| Developed   | Building  | Dhaka    | 0       |
| Female | 29  | 0   | 0   | 0   | Paltan    | Undeveloped | Other     | Dhaka    | 0       |
| Female | 63  | 1   | 1   | 0   | Motijheel | Developed   | Other     | Dhaka    | 1       |
| Male   | 22  | 0   | 0   | 0   | Gendaria  | Undeveloped | Building  | Dhaka    | 0       |

---

### **Primary Target Audience**
- **Healthcare Professionals:** Aids doctors, epidemiologists, and public health officials in assessing a patient's risk of Dengue and recommending further tests or treatment.
- **Government & Health Organizations:** Facilitates disease surveillance, outbreak prediction, and efficient allocation of healthcare resources.
- **Patients & General Public:** Enables individuals to assess their risk level and take preventive actions before visiting a doctor.

---

### **Technologies Used**
- **Machine Learning**: Logistic Regression, Random Forest, KNN, Decision Trees
- **Python Libraries**: scikit-learn, pandas, numpy, joblib
- **Data Preprocessing**: Imputation, Scaling, Encoding
- **Model Evaluation**: Accuracy, Confusion Matrix
