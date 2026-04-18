# 💬 WhatsApp Chat Analyzer

A comprehensive data analysis tool built with **Streamlit** that provides deep insights into your WhatsApp conversations. Whether it's a group chat or a one-on-one message, this app helps you visualize activity, frequency, and communication patterns.

---

## ✨ Key Features

- **Overall Statistics**: Total messages, words, media shared, and links shared.
- **Monthly & Daily Activity Maps**: See which months or days were the most active.
- **Weekly Activity Grid**: Heatmap showing the busiest times of the day throughout the week.
- **Most Active Users**: Leaderboard of the top contributors in a group chat.
- **Word Cloud**: Visual representation of the most frequently used words.
- **Common Word Analysis**: Bar charts of the most used words (filtered to exclude common "stop words").
- **Emoji Analysis**: Breakdown of the most used emojis in the conversation.

---

## 🚀 How to Use

1. **Export Chat**: Open WhatsApp on your phone -> Go to a chat -> Click the three dots -> More -> Export Chat -> **Without Media**.
2. **Download**: Save the `.txt` file to your computer.
3. **Upload**: Run this app and upload the `.txt` file using the sidebar.
4. **Analyze**: Click "Show Analysis" to generate the report!

---

## 🛠️ Tech Stack

- **Python**: Core logic.
- **Streamlit**: Web interface.
- **Pandas**: Data manipulation and cleaning.
- **Matplotlib & Seaborn**: Data visualization and heatmaps.
- **WordCloud**: Visual word summaries.
- **URLExtract**: Extracting and counting shared links.

---

## 💻 Local Installation

To run this project on your local machin

e, follow these steps:

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/Sibghat-629/whatsapp-chat-analysis.git
   cd whatsapp-chat-analysis
