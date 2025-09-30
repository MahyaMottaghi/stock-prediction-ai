
# Stock Prediction Using AI

This project explores how **artificial intelligence** can be applied to stock price prediction, combining traditional machine learning with deep learning and NLP methods.  

The goal was to evaluate multiple models on historical stock data (2020–2024) and compare their ability to capture patterns, trends, and sentiment.  

---

## 🔍 Models Explored

- **Linear Regression** – simple baseline  
- **LSTM (Long Short-Term Memory)** – sequence modeling for time series  
- **Graph Neural Networks (GNNs)** – capturing relationships across stocks  
- **Reinforcement Learning (RL)** – simulating trading strategies  
- **Generative Adversarial Networks (GANs)** – generating synthetic stock data  
- **Large Language Models (LLMs)** – sentiment analysis from financial news & social media  

---

## 📂 Project Contents

- 📓 [Jupyter Notebook: `AI_EXP_Setup.ipynb`](AI_EXP_Setup.ipynb)
- 📑 [Presentation: `Stock Prediction Using AI.pdf`](Stock%20Prediction%20Using%20AI.pdf) 

For a deeper dive into results, please see the **presentation PDF**.

---

## 📊 Key Results & Insights

- **LSTM** performed best overall for smoother stock patterns (Google, Tesla), but struggled with noisy data (Apple).  
- **RL (PPO)** showed profit in simulations but risks overfitting when trained on limited data.  
- **GNNs** revealed structure but suffered from class imbalance.  
- **GANs** produced realistic-looking data and confused the discriminator, showing convergence.  
- **LLMs** extracted sentiment signals that aligned with market movements, especially for Microsoft and Amazon.  

---

## 🛠️ Tech Stack

- Python, Jupyter Notebook  
- Libraries: NumPy, Pandas, Matplotlib, scikit-learn, TensorFlow/Keras, PyTorch Geometric, stable-baselines3, yfinance  

---

## 👥 Credits

This was a **group project** completed for academic purposes.  

Contributors:  
- Luciana Alvarado  
- Jaelen Galindo  
- Mahya Mottaghi  


---
