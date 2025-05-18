# **DeepCare: Predicting Patient Drop-off Using Big Data**

## **Overview**
**DeepCare** is a data mining and machine learning project aimed at predicting patient drop-off using large-scale hospital data. We integrated and processed multiple datasets—**demographics**, **visits**, and **logs**—engineered relevant features, and trained machine learning models to classify patients by dropout risk.

---

## **Tech Stack**
- **Python 3.11**
- **Apache Spark (PySpark)**
- **Google Colab**
- **Power BI**
- **Hadoop** (for XML and CSV parsing)

---

## **📊 Dataset**
We worked with three anonymized datasets:

- **Demographics**: Age, gender, income, etc.
- **Visits**: Appointment type, satisfaction, cost, etc.
- **Logs**: Event-level medical logs and timestamps

---

## **Machine Learning**

### **Clustering**
- **KMeans** used to segment patients into 3 behavioral groups.

### **Models**
- **Logistic Regression**
- **Random Forest**
- **Gradient Boosted Trees (GBT)**

✅ **Best Model**: GBT  
📈 **AUC Score**: 0.5675
📈 **Accuracy**: 0.9105

---

## **Results**
- **Segment 1** had the highest dropout rate.
- Drop-off prediction is **moderately effective** with room for optimization.
- Visualizations created in **Power BI** provide actionable insights into patient behavior and dropout patterns.

---

## **Future Scope**
- Add **time-series features** and **deep learning** architectures.
- Enable **real-world deployment** for continuous learning and feedback loops.
- Develop **better intervention strategies** to retain high-risk patients.

---

## **File Notice**
Due to size limitations on GitHub, datasets are not directly uploaded.  
You can access the full datasets through the **Google Drive link** provided in the `datasets_link.txt` file.

---

