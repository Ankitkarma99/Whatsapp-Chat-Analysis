# **📊 WhatsApp Chat Analyzer (Streamlit + Python)**

[![Python](https://img.shields.io/badge/Python-3.10-blue)]()
[![Streamlit](https://img.shields.io/badge/Streamlit-App-red)]()
[![Pandas](https://img.shields.io/badge/Pandas-Data_Analysis-green)]()
[![Matplotlib](https://img.shields.io/badge/Matplotlib-Visualization-orange)]()
[![Seaborn](https://img.shields.io/badge/Seaborn-Graphs-blue)]()
[![License](https://img.shields.io/badge/License-MIT-green)]()

---

## 📘 **Overview**

The **WhatsApp Chat Analyzer** is a Streamlit-based application that helps users analyze their WhatsApp chat data to understand message patterns, user activity, emojis, timelines, and more.
It converts exported WhatsApp text files into visual insights.

---

## 🚀 **Features**

### ✔️ Chat Statistics

* Total messages
* Word count
* Total media shared
* Links shared

### ✔️ User Insights

* Most active users
* User-level analysis

### ✔️ Word & Emoji Analysis

* Most common words (stopwords removed)
* Emoji frequency analysis
* Word usage distribution

### ✔️ Timeline Visualizations

* Monthly timeline
* Daily timeline

### ✔️ Activity Maps

* Most active day
* Most active month
* Activity heatmap (hour × weekday)

---

## 🛠 **Tech Stack**

* **Python 3.10+**
* **Streamlit**
* **Pandas**
* **Matplotlib**
* **Seaborn**
* **URLExtract**
* **Emoji**
* **Regex**

---

## 📁 **Project Structure**

```
📦 whatsapp-chat-analyzer
 ┣ 📜 app.py
 ┣ 📜 helper.py
 ┣ 📜 preprocessor.py
 ┣ 📜 stop_hinglish.txt
 ┣ 📜 requirements.txt
 ┗ 📜 README.md
```

---

## 📥 **How to Install**

### 1️⃣ Clone the repository

```bash
git clone https://github.com/your-username/whatsapp-chat-analyzer.git
cd whatsapp-chat-analyzer
```

### 2️⃣ Install dependencies

```bash
pip install -r requirements.txt
```

### 3️⃣ Run the Streamlit app

```bash
streamlit run app.py
```

---

## 📄 **How to Export WhatsApp Chat File**

1. Open WhatsApp
2. Go to any chat → tap menu (⋮)
3. Click **More**
4. Choose **Export Chat**
5. Select **Without Media**
6. Save `.txt` file
7. Upload it in the app

---

## 📊 **Analysis Output**

### 🔹 1. Top Statistics

Message count, word count, media count, link count.

### 🔹 2. Most Busy Users

Bar chart + percentage distribution.

### 🔹 3. Most Common Words

Shows frequently used words after removing stop-words.

### 🔹 4. Emoji Analysis

* Emoji usage table
* Emoji pie chart

### 🔹 5. Timeline Analysis

* Month-wise trend
* Day-wise trend

### 🔹 6. Activity Maps

* Most active day
* Most active month
* Activity heatmap

---

## 📄 **File Descriptions**

### **app.py**

Main Streamlit app that manages UI, charts, and logic.

### **preprocessor.py**

Cleans WhatsApp text and converts it into a structured DataFrame.

### **helper.py**

Contains all analysis functions:

* Stats calculation
* Word analysis
* Emoji extraction
* Timeline creation
* Activity maps

### **stop_hinglish.txt**

List of Hinglish stopwords removed during word analysis.

---

## 🤝 Contribution

Pull requests and improvements are always welcome.

---

## 📄 License

This project is licensed under the **MIT License**.

---
