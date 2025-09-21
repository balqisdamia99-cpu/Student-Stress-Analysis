# Analysis and Prediction of Stress Factors Among College Students
This project analyzes factors that affect student stress levels based on a national survey dataset. The analysis was performed using a Random Forest Classifier to predict the `stress_level` category.

* **File Name**: `StressLevelDataset.csv`
* **Number of Data Points: 1100 rows × 21 columns**
* **Target:** `stress_level` (3 classes)
* **Dataset Link:** https://www.kaggle.com/datasets/mdsultanulislamovi/student-stress-monitoring-datasets/data
* **Open in Google Colab:** https://colab.research.google.com/drive/1RtiUCX3CXCnqcbO4BlOYnymo85XFSd3R?usp=sharing

## Analysis Process
1. Data loading & initial exploration (EDA) → check structure, target distribution, unique values.
2. Visualization of stress factors → psychological, academic, social, environmental.
3. Preprocessing → check missing values (none), encoding (not necessary, all numeric), normalization (optional).
4. Modeling with Random Forest Classifier → predict `stress_level`.
5. Model evaluation → confusion matrix & classification report.
6. Feature importance interpretation → dominant factors causing student stress.

## Insights & Findings
* The **Random Forest** model was chosen because the target (`stress_level`) is **categorical classification**, not regression.
* **Model accuracy**: **89.1%**.
* **Dominant factors affecting stress**:
  * `blood_pressure`
  * `sleep_quality`
  * `teacher_student_relationship`
  * `academic_performance`
* Visualization: *Horizontal bar chart (feature importance).*

## Conclusion & Recommendation
1. Students need to manage their study and sleep schedules to keep stress under control.
2. Campuses should strengthen academic support, counseling, and faculty-student relationships.
3. Social factors such as peer pressure and bullying also need to be monitored as they have long-term effects.

## AI Support Explanation
* IBM Granite → used to assist with dataset exploration, feature importance interpretation, and providing analysis suggestions.
* Google Gemini / ChatGPT → assists with compiling insights and conclusions.
