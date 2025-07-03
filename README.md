# 📊 WhatsApp Chat Analyzer

A **Streamlit** web app to analyze WhatsApp chat exports with insights like:
- Most active users
- Common words
- Emoji usage
- Word cloud
- Activity heatmaps and timelines

---

## 🚀 Features

- 📈 **Top Statistics** – messages, words, media, and links
- 📅 **Daily & Monthly Timeline** – trends over time
- 📊 **Activity Map** – busiest days and months
- 🔥 **Heatmap** – weekly activity patterns
- 👑 **Most Active Users** – in group chats
- ☁️ **Word Cloud** – most used words after removing stop words
- 🗣️ **Common Words** – ranked frequency
- 😂 **Emoji Analysis** – usage count and pie chart

---

## 🧠 Logic & Libraries Used

- `pandas` – for data processing
- `matplotlib`, `seaborn` – for charts and plots
- `emoji`, `wordcloud`, `urlextract` – for emojis, word cloud and link detection
- `streamlit` – for creating the web-based interface

---

## 📁 Project Structure


├── app.py                # Main Streamlit app
├── helper.py             # Logic for statistics, charts, emojis, etc.
├── preprocessor.py       # WhatsApp chat text to clean DataFrame
├── stop_hinglish.txt     # Custom stopwords file
├── Procfile              # For deployment (e.g., on Heroku)


## 🧪 How to Use

1. Export your WhatsApp chat as `.txt` (without media)
2. Run the app (instructions below)
3. Upload the file in the sidebar
4. Choose a user or "Overall"
5. Click **Show Analysis**

