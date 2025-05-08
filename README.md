# Heart Disease Prediction using Machine Learning

This project explores the use of **machine learning techniques to predict heart disease** using clinical and demographic data. It leverages preprocessing techniques to clean and balance the dataset, and implements a **neural network** built with TensorFlow-Keras to predict the likelihood of heart disease in patients.

---

## Dataset Overview

The dataset contains **medical attributes** for multiple individuals and is used to classify whether a person has heart disease (`target=1`) or not (`target=0`).

### Attributes Used:

| Feature      | Description |
|--------------|-------------|
| `age`        | Age of the patient |
| `sex`        | Gender (0: Female, 1: Male) |
| `cp`         | Chest pain type (0–3) |
| `trestbps`   | Resting blood pressure |
| `chol`       | Serum cholesterol in mg/dl |
| `fbs`        | Fasting blood sugar > 120 mg/dl (1 = true, 0 = false) |
| `restecg`    | Resting electrocardiographic results |
| `thalach`    | Maximum heart rate achieved |
| `exang`      | Exercise-induced angina (1 = yes, 0 = no) |
| `oldpeak`    | ST depression induced by exercise |
| `slope`      | Slope of the peak exercise ST segment |
| `ca`         | Number of major vessels colored by fluoroscopy |
| `thal`       | Thalassemia type |
| `target`     | 1 = Heart disease, 0 = No disease |

---

## Preprocessing Steps

- ✅ Removed outliers  
- ✅ Handled missing/NaN values  
- ✅ Balanced the dataset using **RandomOverSampler** from `imbalanced-learn`  
- ✅ Applied **StandardScaler** for feature scaling

---

## Model Details

- Built using **Keras Sequential API**
- Final layer uses **Sigmoid activation** for binary classification
- Loss function: `binary_crossentropy`
- Optimizer: `adam`
- Evaluation metric: `accuracy`

---

## Key Contributions

- Cleaned and balanced the dataset
- Built a robust neural network classifier
- Achieved reliable performance for heart disease prediction
- Printed a full classification report and accuracy score

---

## Libraries Used

| Library         | Purpose |
|-----------------|---------|
| NumPy, Pandas   | Data processing |
| Seaborn, Matplotlib | Visualization |
| Imbalanced-learn | Dataset balancing |
| scikit-learn    | Preprocessing, evaluation, splitting |
| TensorFlow Keras | Model building and training |
| os              | Path and file operations |

---

## License

This project is open-source and free to use for educational purposes.

---

## Author

- **Ibrahim Abid**  
  - Roll Number: `i21-0298`  
  - Program: BS AI, FAST NUCES Islamabad

---



