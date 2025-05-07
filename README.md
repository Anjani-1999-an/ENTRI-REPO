 🧠 Mental Health State Detection Using ML

A machine learning project to classify individuals' mental health states based on physiological and digital exposure data from the Digital Exposome Dataset.

---

 📂 Dataset

* **Source**: [Mendeley Data](https://data.mendeley.com/)
* **File**: `DigitalExposome Dataset.csv`
* **Features**: Various physiological/digital behavior indicators
* **Target**: `Label` column representing mental health state (e.g., stressed vs. normal)



 🧠 ML Models Used

* **Algorithms**:

  * Logistic Regression
  * K-Nearest Neighbors (KNN)
  * Decision Tree
  * Random Forest
  * Gradient Boosting
  * AdaBoost
  * Support Vector Classifier (SVC)

* **Libraries**:

  * `pandas`, `numpy` for data handling
  * `scikit-learn` for ML models and evaluation
  * `matplotlib`, `seaborn` (optional for plots)

---

## 📊 Evaluation Metrics

* Accuracy Score (primary)
* Grid Search with Cross-Validation (for hyperparameter tuning)

---

## 📈 Results (Sample Output)

| Model               | Accuracy (%) | Best Hyperparameters                      |
| ------------------- | ------------ | ----------------------------------------- |
| Logistic Regression | 91.23        | `C: 1`                                    |
| KNN                 | 88.75        | `n_neighbors: 5`                          |
| Decision Tree       | 86.90        | `max_depth: 5`                            |
| Random Forest       | 93.10        | `n_estimators: 100`, `max_depth: 7`       |
| Gradient Boosting   | 92.30        | `n_estimators: 100`, `learning_rate: 0.1` |
| AdaBoost            | 90.85        | `n_estimators: 50`, `learning_rate: 0.1`  |
| SVC                 | 92.00        | `C: 1`, `kernel: rbf`                     |



 🚀 How to Run

```bash
# Clone the repo
git clone https://github.com/your-username/mental-health-detector.git
cd mental-health-detector

# Install dependencies
pip install -r requirements.txt

# Run the model
python mental_health_classifier.py
```


✅ Folder Structure

```
mental-health-detector/
├── DigitalExposome Dataset.csv   # Dataset
├── mental_health_classifier.py   # Main ML script
├── requirements.txt              # Libraries list
├── README.md                     # Project overview (this file)
```

 🧾 Conclusion

This project shows that classical machine learning models can effectively predict mental health states using digital and physiological indicators. Future work includes:

* Adding deep learning models
* Integrating time-series or longitudinal data
* Deploying as a web app (e.g., Streamlit or Flask)

