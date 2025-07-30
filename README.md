# 🤖 Ultimate Chatbot by Argon Development

A powerful and stylish Discord chatbot built using the latest features of `discord.js` and integrated with the **Groq API** for ultra-fast, intelligent AI responses.

> ✨ This bot is crafted to outperform other AI bots like Xavier – it’s minimal, responsive, and smarter.

---

## 🚀 Features

- ⚡ Instant AI Chat using **Groq's Mixtral / LLaMA 3 / Gemma models**
- 💬 Slash command support with autocomplete
- 🧠 Context-aware replies in threads and replies
- 🛠️ Easy customization and modular command structure
- 🧼 Clean code and aesthetic response formatting
- 🚫 No image generation – Pure fast chat AI

---

## 📦 Setup Instructions

> Make sure you have Node.js `v20+` installed.

### 1. Clone the repo

```bash
git clone https://github.com/FANGUYSS/Ultimate-Chatbot.git
cd Ultimate-Chatbot
```

### 2. Install dependencies

```bash
npm install
```

### 3. Fill in your `.env` file

Create a `.env` file and add the following:

```
DISCORD_TOKEN=your_discord_bot_token
CLIENT_ID=your_discord_application_id
GROQ_API=your_groq_api_key
```

### 4. Deploy Commands

```bash
node deploy.js
```

### 5. Run the Bot

```bash
node ArgonDev.js
```

---

## 📁 Folder Structure

```
Ultimate-Chatbot/
├── commands/         # All slash command files
├── events/           # Event listeners (ready, interaction)
├── utils/            # Utility functions (chat handler, etc.)
├── ArgonDev.js       # Main bot script
├── package.json
└── .env              # Your secret keys (not uploaded)
```

---

## 🔐 License

This project is licensed under the terms of the `MIT` License.  
See the `LICENSE` file for details.

---

## 📢 About

Built with ❤️ by **Argon Development**  
📺 YouTube: [@argondevs](https://www.youtube.com/@argondevs)
