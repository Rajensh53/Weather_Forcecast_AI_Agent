# 🌤️ Weather Forecast AI Agent – n8n Workflow

This is a mini project built using n8n – an open-source workflow automation tool.  
The **Weather Forecast AI Agent** automates the process of checking weather updates and emailing a custom weather report using AI.

---

## 📌 Features

- Fetches real-time weather data from **Open-Meteo API**
- Uses **DeepSeek Chat LLM** via OpenRouter for smart summarization
- Sends a personalized weather forecast via **Gmail**
- Completely automated using n8n’s no-code workflow builder
- Includes simple memory and agent logic for conversational interaction

---

## 🧠 How It Works

1. **Trigger**: The workflow is initiated via a chat command trigger in n8n.
2. **LLM Integration**: An AI language model (DeepSeek Chat via OpenRouter) interprets the input and prepares the context.
3. **Memory Buffer**: Contextual memory is used for interaction continuity.
4. **Weather Data Fetch**: It fetches hourly weather and rain data from Open-Meteo API.
5. **Email Send**: A personalized weather forecast is generated and sent to a configured email address via Gmail.

---

## 📤 Email Sample Output

> 📬 Subject: “Today’s Forecast at a Glance”  
> ☁️ Message: “Expect a mild afternoon with a chance of light rain. Stay dry and enjoy your day!”

---

## ⚙️ Tools & APIs Used

- 🧠 LLM: DeepSeek Chat via [OpenRouter](https://openrouter.ai/)
- ☁️ Weather API: [Open-Meteo](https://open-meteo.com/)
- 📧 Email: Gmail OAuth2 Integration
- ⚙️ Automation Platform: [n8n](https://n8n.io/)
