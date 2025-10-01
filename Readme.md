# 📩 SMS Spam Detection

An **AI-powered SMS Spam Detection system** that classifies SMS messages as **Spam** or **Not Spam**.  
Built with **Python** and deployed using **Streamlit**, this project applies **Machine Learning** and **NLP** techniques to detect spam with high precision.  

---

## 🚀 Overview

This project takes an SMS as input and predicts whether it is spam or not spam.  
It uses **classical ML models** trained on the SMS Spam Collection dataset and provides an easy-to-use **web interface** for real-time predictions.

---

## 🛠️ Technology Stack

- **Programming Language:** Python  
- **Libraries:** Scikit-learn, Pandas, NumPy, Matplotlib, Seaborn  
- **Web Deployment:** Streamlit  

---

## ✨ Features

- 📥 **Data Collection** – Curated dataset from Kaggle  
- 🧹 **Data Cleaning & Preprocessing** – Tokenization, stemming, stop-word removal, lowercase conversion  
- 📊 **Exploratory Data Analysis (EDA)** – Word clouds, frequency plots, correlation heatmaps, bar/pie charts  
- 🤖 **Model Building & Selection** – Naive Bayes, Random Forest, KNN, Decision Tree, Logistic Regression, ExtraTreesClassifier, SVC  
- 🏆 **Best Model Selection** – Achieved **100% precision**  
- 🌐 **Web Deployment** – User-friendly Streamlit web app for real-time predictions  

---

## 📂 Dataset

- **Source:** [Kaggle – SMS Spam Collection Dataset](https://www.kaggle.com/datasets/uciml/sms-spam-collection-dataset)  
- **Size:** 5,500+ labeled SMS messages  
- **Labels:** Spam / Not Spam  

---

## 📈 Exploratory Data Analysis

- Count of characters, words, and sentences per message  
- Spam vs Ham distribution analysis  
- Word frequency analysis for both spam and non-spam texts  
- Word clouds for spam and non-spam categories  
- Correlation heatmaps and descriptive statistics  

---

## 🧠 Model Building

Tried multiple classifiers:

- ✅ Naive Bayes  
- ✅ Random Forest  
- ✅ KNN  
- ✅ Decision Tree  
- ✅ Logistic Regression  
- ✅ ExtraTreesClassifier  
- ✅ SVC  

📌 Final Model: **Naive Bayes (Best Precision: 100%)**  

---

## 💻 Usage

To run this project on your local machine:

1. **Clone the repository**

    ```bash
    git clone https://github.com/your-username/sms-spam-detection.git
    cd sms-spam-detection


2. **Install dependencies**

     ```bash
    pip install -r requirements.txt


3. **Run the app**

     ```bash
    streamlit run app.py


4. **Open in browser**

     ```bash
    Go to http://localhost:8501

## 🔮 Future Enhancements

  - 🌍 Multi-language spam detection
  
  - 🔎 Emotion & tone detection beyond spam/ham
  
  - 📊 Interactive dashboard with more visualizations
  
  - 📑 Export results to Excel / PDF reports
  
  - ⚡ Optimized lightweight model for mobile deployment

## 🤝 Contributing

Contributions are welcome! 🚀

1. **Fork the repo**

2. **Create a branch**

     ```bash
    git checkout -b feature-name


3. **Commit changes**

     ```bash
    git commit -m "Add new feature"


4. **Push the branch**

     ```bash
    git push origin feature-name


5. **Create a Pull Request 🎉**


## 🙌 Acknowledgements

### A huge thank you to Microsoft, SAP Labs, Edunet Foundation, and AICTE for providing this learning opportunity under TechSaksham.
