# Prognostic Evaluation of Cervical Cancer Using Various Classifiers

<p align="center">
  <img src="./visuals/Banner.jpg" alt="Cervical Cancer ML" width="600"/>
</p>

## 📄 Overview
Cervical cancer is one of the most prevalent malignancies affecting women worldwide. Early detection significantly reduces mortality, yet identifying early signs is challenging, especially in countries with limited screening programs.  

This project leverages **machine learning models** to **predict cervical cancer risk** based on patient data, enabling timely diagnosis and intervention. The work is based on the **Kaggle Cervical Cancer Dataset** and has been published in IEEE: [Paper Link](https://ieeexplore.ieee.org/document/10058662).

---

## 🧰 Technologies Used
- **Languages:** Python  
- **Libraries & Tools:** scikit-learn, Pandas, NumPy, Matplotlib, Seaborn  
- **ML Models:** Decision Trees (DT), Logistic Regression (LR), Random Forest (RF), Support Vector Machines (SVM), AdaBoost, Artificial Neural Networks (ANN)  
- **Other:** Jupyter Notebook

---

## 🗂️ Dataset
- **Source:** Kaggle Cervical Cancer Dataset  
- **Description:** 858 unique cases with 36 attributes including Cytology, Hinselmann, Biopsy, and Schiller types.  
- **Goal:** Predict risk of cervical cancer using patient history and medical attributes.  

---

## 🚀 Workflow
1. **Descriptive Analysis:** Explored distributions, correlations, and trends among risk factors.  
2. **Data Preprocessing:** Handled missing values, normalized features, and encoded categorical variables.  
3. **Modeling:** Implemented multiple ML classifiers: DT, LR, RF, SVM, AdaBoost, and ANN.  
4. **Evaluation:** Compared model performance using Accuracy, F1-Score, and ROC-AUC metrics.  
5. **Visualization:** Plotted feature importance, confusion matrices, and predictive outcomes.  

---

## 📊 Key Results
| Model           | Accuracy | Notes |
|-----------------|---------|-------|
| SVM             | 87%    | Excellent early-stage prediction |
| AdaBoost        | 89%    | Highly reliable |
| Decision Tree   | 86%    | Accurate classification |
| Logistic Reg.   | 83%    | Strong baseline model |
| Random Forest   | 81%     | Slightly lower than top models |
| ANN             | 84%     | Comparable to RF |

- The study shows that **SVM, AdaBoost, DT, and LR** can accurately detect early cervical cancer using diagnostic data.

---

## 🔗 Published Paper
- [IEEE Xplore Link](https://ieeexplore.ieee.org/document/10058662)  
- Citation:  
`Tulasi Thotakura et al., "Prognostic Evaluation of Cervical Cancer Using Various Classifiers," IEEE, 2023.`

---
