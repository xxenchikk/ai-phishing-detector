# 🛡️ AI Phishing Detector

A simple web-based phishing detection project that analyzes messages for common signs of phishing and social engineering.

## 📌 About

Phishing messages often use urgency, suspicious requests, fake prizes, password requests, and other social engineering techniques.

This project analyzes the text entered by a user and identifies common phishing indicators.

## ✨ Features

- Analyzes suspicious emails and messages
- Detects common phishing keywords and patterns
- Shows a High or Low phishing risk
- Explains which suspicious indicators were detected
- Provides basic security advice
- Works directly in the browser

## ⚙️ How It Works

The current prototype uses rule-based text analysis.

It checks the submitted message for indicators such as:

- urgent
- password
- click here
- verify
- account suspended
- bank account
- winner
- prize
- login
- immediately

If multiple suspicious indicators are detected, the message is classified as a higher phishing risk.

## 🚀 Live Demo

The project is deployed using GitHub Pages:

https://xxenchikk.github.io/ai-phishing-detector/

## 🛠️ Technologies

- HTML
- CSS
- JavaScript
- GitHub Pages

## 🔮 Future Development

The next version could integrate an AI/LLM model to analyze context instead of relying only on predefined keywords, detect more advanced social engineering techniques, and provide more detailed explanations.

## ⚠️ Disclaimer

This project is an educational prototype and should not be used as a replacement for professional cybersecurity tools.
