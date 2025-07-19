# 🛡️ Phishing Website Detection using Machine Learning (Random Forest)

Detecting phishing websites is crucial for protecting users from online fraud and cyberattacks. This project uses a **Random Forest** algorithm to classify whether a website is legitimate or phishing based on various features extracted from the URL and website behavior.

## 📌 Project Overview

Phishing is a cybercrime where attackers impersonate legitimate websites to steal sensitive user information like usernames, passwords, and credit card details. In this project, we use machine learning to automate phishing detection using a dataset of real and phishing websites.

## ⚙️ Features Used

The model uses multiple features derived from URLs, such as:

- Presence of IP address in URL  
- URL length  
- Use of `@` symbol  
- Redirects and HTTP/HTTPS checks  
- SSL certificate status  
- Domain registration length  
- Number of subdomains  
- Favicon, iFrame, mouseover, and popup behaviors

## 🧠 Model Used

- **Random Forest Classifier**
  - An ensemble learning method that combines multiple decision trees.
  - Helps reduce overfitting and improves prediction accuracy.
  - Suitable for handling large feature sets with better interpretability.

## 📊 Performance Metrics

- **Accuracy**: ~97%
- **Precision, Recall, F1-score**: High values indicating robustness
- **Confusion Matrix**: Clear distinction between phishing and legitimate websites

## 🔍 How it Works

1. Preprocess the dataset (handle nulls, encode labels, normalize values).
2. Split the dataset into training and testing sets.
3. Train the Random Forest model.
4. Evaluate performance using test data.
5. Predict new URLs to check if they are phishing or not.

## 🖥️ Technologies Used

- Python
- scikit-learn
- pandas
- NumPy
- matplotlib / seaborn (for visualization)
- Jupyter Notebook / Google Colab

## 🚀 How to Run

1. Clone the repo:
   ```bash
   git clone https://github.com/your-username/phishing-detection.git
   cd phishing-detection
