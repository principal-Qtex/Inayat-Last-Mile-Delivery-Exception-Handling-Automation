# Inayat Last-Mile Delivery Exception Handling Automation

An intelligent exception detection and automated resolution system for logistics. This project utilizes machine learning classification to identify delivery anomalies (such as delays, location mismatches, and failed attempts) and leverages rule-based workflows to automatically escalate or resolve issues.

---

## 🔄 Workflow

1. **Anomaly Detection:** ML classifier flags deviations (predicted vs. actual delivery time, geolocation bounds, retry count thresholds).
2. **Exception Categorization:** Routes issues to the appropriate handler (delay, address mismatch, access issue, or proof-of-delivery failure).
3. **Automated Actions:** Triggers retry logic, customer notifications, driver reassignments, or supervisor escalations.
4. **Optimization:** Performs predictive rerouting and resource allocation to minimize future exceptions.

---

## 🛠 Tech Stack

* **Language:** Python
* **Machine Learning:** `scikit-learn`, XGBoost
* **Data Handling:** `pandas`
* **Workflow Engine:** Rule Engines
* **Data Sources:** Mock logistics datasets

---

## 📊 Key Metrics

* **Exception Detection Accuracy:** Precision and recall in identifying delivery anomalies.
* **Auto-Resolution Rate:** Percentage of exceptions resolved without human intervention.
* **Delivery Time Variance:** Overall reduction in unexpected delivery delays.
