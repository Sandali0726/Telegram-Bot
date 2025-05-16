
# 🤖 Telegram Joke Bot

A fun and interactive Telegram bot that generates AI-powered jokes using [Langchain](https://www.langchain.com/), [Hugging Face API](https://huggingface.co/), and is deployed on [Railway](https://railway.app/). Built during the **Dev Town Bootcamp** to demonstrate Python automation, AI integration, and bot deployment.

---

## 📸 Demo
![Image](https://github.com/user-attachments/assets/07bb86fc-9002-40b4-ac25-2df36a73940b)

---

## ⚙️ Features

- 🔁 Instant joke generation via commands
- 💬 Custom keyword input for topic-based humor
- 🧠 LLM integration with Hugging Face + Langchain
- 📊 Real-time monitoring with LangSmith
- 🚀 Deployment via Railway

---

## 🧪 Requirements

From `requirements.txt`:

```
langchain
python-dotenv
langchain_groq
langchain_community
python-telegram-bot
```

---

## 🛠️ Local Setup

1. **Clone the repository**
   ```bash
   git clone https://github.com/your-username/Telegram-Bot.git
   cd Telegram-Bot
   ```

2. **Install dependencies**
   ```bash
   pip install -r requirements.txt
   ```

3. **Configure environment variables**

   Create a `.env` file:
   ```env
   TELEGRAM_BOT_TOKEN=your_telegram_bot_token
   HUGGINGFACE_API_KEY=your_huggingface_token
   ```

4. **Run the bot**
   ```bash
   python main.py
   ```
---

## ☁️ Deployment (Railway)

You can easily deploy your bot using [Railway](https://railway.app/).

![Image](https://github.com/user-attachments/assets/1919d491-5397-4cd3-a8bf-504486ecd74d)

### Steps:
1. Create a new Railway project.
2. Connect your GitHub repo.
3. Set environment variables in Railway.
4. Deploy 🚀

---

## 📊 Monitoring with LangSmith

![Image](https://github.com/user-attachments/assets/ce059220-34a6-4801-8b5d-4160b6633203)

### Tracked Metrics:
- ✅ Run Count: **20**
- ⏱️ Median Latency: **0.58s**
- 🧠 Total Tokens: **2,387**
- ❌ Error Rate: **0%**

LangSmith helps monitor LLM performance with:
- Prompt input/output logs
- Error tracking
- Token usage
- Latency analysis

---

## 🧠 Built With

- 🐍 Python
- 📡 `python-telegram-bot`
- 🧠 `langchain`, `langchain_community`, `groq`
- 🤗 Hugging Face API
- 🌍 Railway (for deployment)
- 🔍 LangSmith (for observability)

---

## 🌟 Show Your Support

If you like this project:
- ⭐ Star the repo
- 🐛 Submit issues or feedback
- 📢 Share with others!

---



