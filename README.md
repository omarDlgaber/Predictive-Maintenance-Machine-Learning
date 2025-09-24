# 🔧 Predictive Maintenance using Machine Learning

## 📌 Project Overview
How do we know a bearing is about to fail… before it actually does?  
This project explores that question using **Machine Learning** applied to **real vibration data** from experimental setups.

The goal: Develop a predictive maintenance system that detects early fault detection in bearings, helping industries reduce downtime, lower costs, and improve safety.

---

## ⚙️ Dataset
| Dataset | Duration | Files | Channels | Faults Observed |
|---------|----------|-------|----------|-----------------|
| **Set 1** | Oct 22, 2003 – Nov 25, 2003 | 2156 | 8 (2 per bearing: x- and y-axis) | Bearing 3: Inner race defect; Bearing 4: Roller element defect |
| **Set 2** | Feb 12, 2004 – Feb 19, 2004 | 984 | 4 (1 per bearing) | Bearing 1: Outer race defect |
| **Set 3** | Mar 4, 2004 – Apr 4, 2004 | 6324 | 4 (1 per bearing) | Bearing 3: Outer race defect | 

---

## 🧠 Methodology
1. **Data Preprocessing** → Cleaning, balancing, cutoff handling (e.g., special case for roller element defect in Set 1).  
2. **Feature Engineering** → Time-domain features from vibration signals.  
3. **Model Training** → Compared multiple ML classifiers.  
4. **Evaluation** → Accuracy, Precision, Recall, F1-score.  

---

## 🎯 Results
- Final model achieved **~87% accuracy** on unseen test data.  
- Key finding: Roller element defect in **Set 1, Bearing 4** showed early critical signs at **81.3% of lifetime**, unlike other bearings.

---

## 💡 Why It Matters
- 💰 **Cost Reduction** → Planned maintenance vs. costly emergency repairs  
- 🛡️ **Safety Enhancement** → Avoid catastrophic failures & hazards  
- ⚙️ **Equipment Longevity** → Extend machinery lifespan  
- 📈 **Production Efficiency** → Minimize downtime, optimize operations  

---

## 🛠️ Tech Stack
- Python 🐍  
- Scikit-learn 🤖  
- Pandas & NumPy 📊  
- Matplotlib 📉  

---

## 📚 References & Dependencies
- **Dataset:**
    - NASA Bearing Dataset: [Kaggle](https://www.kaggle.com/datasets/vinayak123tyagi/bearing-dataset/data)
    - IMS Bearing Dataset: Raw vibration signal data from the NSF I/UC Center for Intelligent Maintenance Systems (IMS), University of Cincinnati

- **Libraries Used:**
    - Data Processing:
        - `numpy`: Numerical computing
        - `pandas`: Data manipulation
    - Visualization:
        - `matplotlib`: Basic plotting
        - `seaborn`: Statistical visualization
    - Machine Learning:
        - `scikit-learn`: Random Forest implementation and metrics
        - `pathlib`: File path handling

---

## 📢 Connect
- [LinkedIn](https://www.linkedin.com/in/omar-adel-726407200/)
