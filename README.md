
# 🤖 Discord Bot in Python

Welcome to the **Python Discord Bot** project — a beginner-friendly yet feature-rich bot crafted using Python and the `discord.py` library. This project is designed to give you hands-on experience building and managing a functional bot on Discord. Whether you're just starting out or brushing up your Python skills, this project will teach you real-world concepts of bot development, event handling, and role-based permissions.

---

## 📌 Project Summary

This bot performs several automated tasks in a Discord server:
- Sends welcome messages to new members.
- Deletes messages containing inappropriate words.
- Responds to commands like `!hello`, `!dm`, `!reply`, and `!poll`.
- Assigns and removes a custom role called **"python coder"**.
- Grants exclusive access to a `!secret` command based on user roles.
- Logs all bot activity using Python's `logging` module.

---

## 💡 What You’ll Learn as a Beginner

By building and running this bot, you’ll:
- Learn how to use the `discord.py` library and command extensions.
- Understand how to use environment variables securely using `python-dotenv`.
- Get familiar with event-driven programming using `async/await`.
- Practice creating custom command functions and managing user roles.
- Learn how to use embeds, direct messages, and reactions on Discord.

---

## ✅ Pros

- 🔰 **Beginner-Friendly**: Simple and clean code structure.
- 🧠 **Educational**: Covers real-world Discord bot functionality.
- 🛠️ **Extensible**: Easy to add more commands and features.
- 🔒 **Secure**: Uses `.env` for token management.
- 🗃️ **Logs**: Logging setup for better debugging.

---

## ⚠️ Cons

- ❌ **No Database**: Role persistence after server restarts isn't supported.
- 🧪 **Basic Moderation**: Limited to simple message deletion.
- 📌 **Hardcoded Role**: The bot currently works with a fixed role name (`"python coder"`).

---

## 🚀 Enhance Your Python Skills

This project reinforces the following Python concepts:
- ✅ Environment variables and file handling
- ✅ Logging and debugging
- ✅ Object-oriented interaction with `discord.ext.commands`
- ✅ Asynchronous programming (`async def`, `await`)
- ✅ Role and permissions management

---

## 🧰 Installation & Setup

### 📦 Install the required dependencies
```bash
pip install -r requirements.txt
