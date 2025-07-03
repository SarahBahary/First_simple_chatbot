

# 🧠 TechGadget Support Chatbot

This project is a simple yet smart customer support chatbot for **TechGadget**, built using Python. It combines **exact matching** and **fuzzy text matching** to provide accurate and flexible responses to user questions.

---

## 💡 Features

* ✅ Instant responses using predefined intents
* 🔍 Fuzzy matching for flexible input handling (via `rapidfuzz`)
* 📦 Covers common support topics like shipping, returns, device reset, and more
* 🔄 Continuous conversation in a loop until the user exits

---

## 🛠 Technologies Used

* Python 3
* [`rapidfuzz`](https://github.com/maxbachmann/RapidFuzz) for fuzzy string matching

---



## ✍️ Example Conversation

```
You: hi  
Bot: Hello! Welcome to TechGadget Support. How can I assist you today?

You: do you sell smart watches  
Bot: Yes, we have a variety of smartwatches. You can check them out on our products page.

You: what are your shipping options?  
Bot: We offer standard, expedited, and overnight shipping.

You: bye  
Bot: Thank you for visiting TechGadget. If you have more questions, feel free to ask. Goodbye!
```

---

## 📂 File Structure

```
chatbot.py       # Main Python script with chatbot logic
README.md        # Project documentation (you’re reading it!)
```

---

## 🔧 Customization

You can extend the chatbot by editing the `responses` dictionary inside `chatbot.py`:

```python
responses = {
    "hi": "Hello! ...",
    "shipping methods": "We offer standard, expedited, and overnight shipping.",
    ...
}
```

---

## 📄 License

This project is licensed under the MIT License.

---
# 🧠 TechGadget Support Chatbot

[![Python](https://img.shields.io/badge/Python-3.8+-blue?logo=python&logoColor=white)](https://www.python.org/)
[![License: MIT](https://img.shields.io/badge/License-MIT-green.svg)](https://opensource.org/licenses/MIT)
[![RapidFuzz](https://img.shields.io/badge/Powered%20By-RapidFuzz-orange)](https://github.com/maxbachmann/RapidFuzz)
[![Issues](https://img.shields.io/github/issues/your-username/techgadget-chatbot)](https://github.com/your-username/techgadget-chatbot/issues)
[![Stars](https://img.shields.io/github/stars/your-username/techgadget-chatbot?style=social)](https://github.com/your-username/techgadget-chatbot/stargazers)

