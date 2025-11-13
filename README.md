# 🎓 University FAQ Chatbot
**By Vishal (Roll No: 2301201222)**  
**Course:** BCA – Section C  

---

## 📚 Overview
This project is a simple **AI-powered FAQ Chatbot** designed to answer university-related queries such as admissions, fees, timetable, hostels, and exams.  
It uses **Natural Language Processing (NLP)** techniques like text preprocessing and similarity matching to understand and respond to student questions.

---

## 🎯 Goal
To create a chatbot that automatically answers common student queries about university information.

---

## 🔑 Concepts Used
- **Text Preprocessing:** Tokenization, stopword removal, lemmatization  
- **TF–IDF Vectorization:** To convert text into numerical form  
- **Cosine Similarity:** To find the closest matching question in the dataset  
- **Rule-based Query Matching**

---

## 🛠 Tools & Libraries
- **Python**  
- **NLTK** – for NLP preprocessing  
- **Scikit-learn** – for TF-IDF and cosine similarity  
- **Pandas** – for handling the dataset  

---

## 🧩 Workflow
1. Preprocess the FAQ dataset (tokenize, remove stopwords, lemmatize).  
2. Preprocess the user input query.  
3. Compute similarity between the user query and dataset questions.  
4. Return the best-matching answer.

---

## 📊 Example Dataset

| Question | Answer |
|-----------|---------|
| How much is the admission fee? | Admission fee is ₹5000. |
| How can I apply for a hostel? | Fill the hostel form online at hostel.university.edu. |
| When will exams start? | Exams will begin in December as per the academic calendar. |

---

## 💻 How It Works (Google Colab or Local)
1. Install dependencies  
   ```bash
   pip install nltk scikit-learn pandas
