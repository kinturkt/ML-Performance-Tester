# ML-Performance-Tester

An interactive **Streamlit** app to train, evaluate, and compare multiple machine learning models on the **NBA player stats dataset**. This tool helps visualize and benchmark model performance for classification tasks such as predicting player positions.

---

## 🚀 Features

- 🔍 Preview NBA dataset (stats, positions, performance)
- 🧪 Run individual ML models:
  - Decision Tree
  - k-Nearest Neighbors (kNN)
  - Naive Bayes
  - Support Vector Classifier (SVC)
  - Linear SVM
- 🛠️ Hyperparameter tuning (C, k, max depth)
- 📊 Visual comparison of Accuracy, Precision, Recall, F1-Score
- 🧾 Confusion matrices + classification reports
- ✅ 10-Fold Cross-Validation support

---

## 💡 How It Works

1. Launch the Streamlit app:
   ```bash
   streamlit run app.py

2. Preview the NBA dataset

3. Use the sidebar to tune hyperparameters

4. Click on any model to train & evaluate

5. See performance metrics and compare models visually

---

🧠 Technologies Used
Python 3
Pandas – Data manipulation
scikit-learn – ML algorithms & metrics
Streamlit – Interactive front-end
Matplotlib – Accuracy comparison chart

--- 

📦 Setup & Installation

1. Clone the repo:
   ```bash
   git clone https://github.com/your-username/model-performance-tester.git
   cd model-performance-tester

2. Install dependencies:
   ```bash
   pip install -r requirements.txt

3. Run the app:
   ```bash
   streamlit run app.py

---

🙌 Author
Kintur Shah
Built with curiosity and a love for clean ML workflows.
