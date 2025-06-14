# 💬 WhatsApp Chat Analyzer – Personal Conversation Insights via Data Science

Welcome to the **WhatsApp Chat Analyzer**, a powerful data science project designed to extract **deep insights**, **visual patterns**, and **engaging statistics** from your exported WhatsApp chat history. Whether it's a one-on-one conversation or a noisy group thread, this tool transforms raw .txt exports into **meaningful storytelling dashboards**.

---

## 📌 Project Highlights

* 📥 **Chat Parsing & Preprocessing**
  Converts raw WhatsApp `.txt` exports into structured data. Cleans and formats messages by sender, date, time, and content type (text, media, links, etc.).

* 📊 **Visual Exploratory Data Analysis (EDA)**

  * Messages over time (monthly, daily)
  * Most active users (for group chats)
  * Word cloud of most frequent terms
  * Emoji analysis
  * Most shared links & media frequency
  * Top user statistics

* 🧮 **Conversation Statistics**

  * Total messages, words, media files, emojis
  * Average messages per day
  * Longest streaks and most active days
  * Most talkative participants

* ⏰ **Time-Based Trends**

  * Hourly and weekly activity heatmaps
  * Night owl vs early bird tendencies
  * Day-wise mood shifts

---

## 🧰 Tools & Libraries Used

* `Pandas` – Data manipulation
* `Matplotlib`, `Seaborn` – Visualizations
* `WordCloud`, `emoji` – Text & emoji insights
* `re`, `datetime` – Parsing and formatting

---

## 📁 Folder Structure

```bash
├── Whatsapp_chat_analysis.ipynb   # Full notebook: cleaning + EDA
├── chat.txt                       # Your exported WhatsApp chat (input)
├── outputs/                       # Generated plots and charts
├── README.md                      # Project documentation
├── requirements.txt               # Python dependencies
```

---

## 💡 Sample Use Case

Export your chat from WhatsApp (Settings → More → Export Chat) and load it into the notebook.

Get answers like:

* Who texts the most?
* What days are the busiest?
* Which emojis are overused? 😂🔥
* Who sends more media than messages?

---

## 🚀 Future Additions

* Streamlit-based web app for uploading and viewing reports
* Sentiment analysis of chat content
* Chat topic modeling (e.g., LDA)
* PDF export of analysis summary

---

## 📜 License

MIT License — use it, remix it, improve it!

---

## 🙌 Contributing

Open to feedback, improvements, or new visualization ideas. PRs welcome!

