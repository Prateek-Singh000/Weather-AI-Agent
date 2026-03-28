# 🌤️ Weather AI Agent – A Claude-Powered Assistant

[![Python](https://img.shields.io/badge/python-3.9+-blue.svg)](https://www.python.org/downloads/)
[![License](https://img.shields.io/badge/license-MIT-green.svg)](LICENSE)
[![AWS Bedrock](https://img.shields.io/badge/AWS-Bedrock-orange)](https://aws.amazon.com/bedrock/)
[![Streamlit](https://img.shields.io/badge/Streamlit-FF4B4B?logo=streamlit&logoColor=white)](https://streamlit.io/)
[![OpenWeatherMap](https://img.shields.io/badge/OpenWeatherMap-API-blue)](https://openweathermap.org/api)

An AI‑powered weather assistant that combines **Amazon Bedrock (Claude 4.5 Sonnet)** with real‑time weather data.  
Ask questions like “What’s the weather like in Tokyo?” and get natural, conversational answers.

This project was built during an **AWS workshop** to demonstrate the fundamentals of agentic AI using **pure Python and the AWS SDK (boto3)** – no heavy frameworks, just clean, readable code.

---

## ✨ Features

- **Natural language understanding** – powered by Claude 4.5 Sonnet via Amazon Bedrock  
- **Real‑time weather data** – fetches current conditions and forecasts from OpenWeatherMap  
- **Two interfaces** – command‑line for quick tests and a **Streamlit** web app for a polished UI  
- **Simple architecture** – no complex orchestration; the AI decides what API calls to make and returns a friendly answer  
- **Easy to extend** – swap the weather API for another service, or add more tools to the agent

---

## 🧠 How It Works
