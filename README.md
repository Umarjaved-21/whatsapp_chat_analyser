# 💬 WhatsApp Chat Analyzer

An interactive and user-friendly platform for analyzing and extracting insights from WhatsApp conversations using Python and Streamlit.

---

## 👀 Overview

**Chat Analyzer** is a tool built to turn your exported WhatsApp chat into visual insights — from top statistics to emoji analysis. Useful for personal reflection, customer communication insights, and educational research.

---

## 🧠 Features

- 📊 **Top Statistics**: Total messages, words, links, media
- 📅 **Timeline Visualizations**: Daily & monthly message trends
- 🔥 **Activity Map**: Weekly heatmap of message frequency
- 🧑‍🤝‍🧑 **User-wise Insights**: Most/least active members in group chats
- ☁️ **Word Cloud**: Visualize most used words (with stop word filtering)
- 😂 **Emoji Analysis**: Pie chart and table of emoji usage
- 📈 **Common Words**: Bar chart of top 20 words

---

## 🔧 Working Process

1. **Export Chat** from WhatsApp as `.txt`  
2. Launch the Streamlit app (`app.py`)  
3. Upload the exported file and select user  
4. Get deep analysis through visualizations

---

## 🛠️ Tech Stack

- **Python Libraries**: 
  - `Streamlit`
  - `Pandas`
  - `Matplotlib`
  - `Seaborn`
  - `WordCloud`
  - `Emoji`
  - `URLExtract`
  - `re`, `collections`, `NumPy`

---

## 🔍 Applications

- **Personal Use**: Understand your texting habits  
- **Professional Use**: Analyze customer support or team chats  
- **Educational Use**: Study group conversations or communication patterns  

---

## 📉 Sample Results

- **Messages**: 308  
- **Words**: 1566  
- **Media Shared**: 116  
- **Links Shared**: 4  

---

## 💻 Run Locally

git clone https://github.com/your-username/whatsapp-chat-analyzer.git
cd whatsapp-chat-analyzer
pip install -r requirements.txt
streamlit run app.py

---

📌 Future Scope
This tool can help organizations understand group dynamics — e.g., identifying most/least active participants, sentiment patterns, etc. It's scalable for real-time dashboarding and team analytics.

⭐ If you like this project, give it a star and share your feedback!
