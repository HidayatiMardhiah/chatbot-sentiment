# 🗨️ Sentiment Analysis Chatbot  

A simple chatbot built with **Logistic Regression** and a **Gradio UI**.  
It classifies user input as positive or negative sentiment and responds conversationally.  

---

## ✨ Features  
- 🧹 Text preprocessing (removes mentions, URLs, punctuation)  
- 🔤 Word representation with **Word2Vec** (compared against Bag of Words)  
- 📊 Sentiment classification using **Logistic Regression** (compared with VADER and Naive Bayes)  
- 📈 Accuracy comparison visualized with a bar graph  
- 🤖 Interactive chatbot UI powered by **Gradio**  
- ✅ Confidence score displayed for predictions  

---

## 📂 Dataset  
This project uses the **[Sentiment140 dataset](http://help.sentiment140.com/for-students/)**.  

Steps:  
1. Download the dataset from the link above  
2. Extract the ZIP file  
3. Place the extracted file in the same folder as the project  

---

## ⚙️ Prerequisites  
- Python 3.x  
- Jupyter Notebook  

---

## 🚀 Demo  

Clone the repository and install dependencies:  

```bash
git clone https://github.com/hidayatimrdiah/chatbot-sentiment.git
cd sentiment-chatbot
pip install -r requirements.txt
