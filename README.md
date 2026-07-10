# Predictive Maintenance of Industrial Machinery Using IBM watsonx.ai AutoAI

## Project Overview

This project was developed as part of the **IBM SkillsBuild AICTE Internship 2026**.

The objective of this project is to develop a machine learning model that predicts industrial machine failures before they occur using operational sensor data. The solution leverages **IBM watsonx.ai Studio** and **AutoAI** to automatically build, evaluate, and deploy the best-performing classification model.

---

## Problem Statement

Develop a predictive maintenance model for industrial machinery capable of predicting different machine failure types based on real-time operational parameters. The solution helps industries perform proactive maintenance, reduce downtime, minimize maintenance costs, and improve equipment reliability.

---

## Technologies Used

- IBM Cloud
- IBM watsonx.ai Studio
- IBM watsonx.ai AutoAI
- Machine Learning
- Snap Random Forest Classifier
- Python
- Jupyter Notebook

---

## Dataset

**Dataset Name:** Predictive Maintenance Dataset

**Machine Learning Task:** Multi-Class Classification

**Target Variable:** Failure Type

**Input Features:**

- Air Temperature [K]
- Process Temperature [K]
- Rotational Speed [rpm]
- Torque [Nm]
- Tool Wear [min]
- Machine Type

---

## Model Details

**Best Model:**
Snap Random Forest Classifier

**Holdout Accuracy:**
99.6%

**Cross Validation Accuracy:**
99.5%

---

## Project Workflow

1. Upload the dataset to IBM watsonx.ai Studio.
2. Create an AutoAI experiment.
3. Automatically generate multiple ML pipelines.
4. Select the best-performing model.
5. Evaluate model performance.
6. Deploy the model as an Online Deployment.
7. Test the deployment using sample machine sensor values.

---

## Repository Contents

- `predictive_maintenance.csv` – Dataset
- `Problem_Statement.pdf` – Official project problem statement
- `Predictive_Maintenance_of_Industrial_Machinery_Using_IBM_watsonx.ai_AutoAI.pptx` – Project presentation
- `Predictive_Maintenance_AutoAI.ipynb` – AutoAI generated notebook
- `Screenshots/` – IBM Cloud project screenshots

---

## Future Scope

- Integration with Industrial IoT (IIoT) sensors
- Real-time machine monitoring
- Automated maintenance alerts
- ERP and CMMS integration
- Deployment across multiple manufacturing plants

---

## Author

**Name:** Gunda Nikitha

**Internship:** IBM SkillsBuild AICTE Internship 2026
