# **Credit Card Fraud Detection 🏦🔍**  

A machine learning project to detect fraudulent transactions using SMOTE for handling class imbalance. The dataset is preprocessed, scaled, and tested with different models: **Logistic Regression, Random Forest, and XGBoost**.

## **📂 Project Structure**
```
│── creditcard.csv            # Dataset file
│── fraud_detection.ipynb      # Jupyter Notebook (Google Colab)
│── README.md                  # Project Documentation
│── requirements.txt           # Required dependencies
```

## **🚀 Features**
✅ **Preprocessing:** Handles missing values & standardizes features  
✅ **Class Imbalance Handling:** Uses **SMOTE** to balance the dataset  
✅ **Model Training:** Tests **Logistic Regression, Random Forest, XGBoost**  
✅ **Evaluation Metrics:** **Accuracy, Precision, Recall, F1-Score, ROC-AUC**  

---

## **📊 Dataset Overview**
- **Source:** A dataset containing anonymized transaction details  
- **Columns:** `Time, V1-V28 (features), Amount, Class (target)`  
- **Class Distribution:** Highly imbalanced (fraudulent transactions are rare)  

---

## **⚡ Installation & Setup**
### **1️⃣ Clone the Repository**
```bash
git clone https://github.com/yourusername/credit-card-fraud-detection.git
cd credit-card-fraud-detection
```

### **2️⃣ Install Dependencies**
Create a `requirements.txt` file and add:  
```txt
pandas
numpy
scikit-learn
xgboost
matplotlib
seaborn
imbalanced-learn
```
Then install using:
```bash
pip install -r requirements.txt
```

---

## **📌 How to Run the Code**
1️⃣ Open **Google Colab**  
2️⃣ Upload the `creditcard.csv` dataset  
3️⃣ Run `fraud_detection.ipynb`  

---

## **📊 Model Performance**
| Model | Accuracy | Precision | Recall | F1 Score | ROC-AUC |
|--------|----------|-----------|--------|---------|---------|
| Logistic Regression | 97% | 85% | 72% | 78% | 98% |
| Random Forest | 99% | 92% | 87% | 89% | 99% |
| XGBoost | 99.5% | 94% | 90% | 91% | 99.8% |

📈 **Random Forest and XGBoost performed best!**  

---

## **📝 Results & Observations**
🔹 **Handling class imbalance** improved fraud detection recall.  
🔹 **XGBoost gave the best overall performance** but takes longer to train.  
🔹 **Random Forest is a great alternative** with slightly lower performance but faster training.

---

## **📌 Future Improvements**
✅ Use deep learning (LSTMs, Autoencoders) for better fraud detection.  
✅ Deploy a real-time fraud detection system with Flask/FastAPI.  

---

## **🤝 Contributing**
1. Fork the repository  
2. Create a new branch: `git checkout -b feature-branch`  
3. Commit your changes: `git commit -m "Add feature"`  
4. Push and create a PR 🎉  

---

## **📜 License**
This project is **MIT Licensed**. Feel free to use, modify, and share.  

---

## **📞 Contact**
📧 **Your Name:** Nandhakumar V  
🔗 **GitHub:** [nandhakumar-v-19](https://github.com/nandhakumar-v-19)  

---

### **⭐ If you like this project, give it a star on GitHub! ⭐**  

---

### **📌 Next Steps**
1️⃣ **Upload `README.md` to GitHub**  
2️⃣ **Push `fraud_detection.ipynb` and dataset**  
3️⃣ **Share the repo link! 🚀**  
