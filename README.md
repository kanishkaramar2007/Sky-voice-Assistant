# ✈️ SkyVoice — Airline Voice Assistant

SkyVoice is a browser-based airline voice assistant prototype that helps passengers get quick answers about flights using **Speech Recognition, NLP, and Speech Synthesis**.

## 🚀 Project Overview

SkyVoice allows users to interact with an airline assistant through voice or text. The system identifies the user's request using lightweight NLP and provides a suitable response using simulated flight data.

The prototype supports queries related to:

- ✈️ Flight Status
- 🛫 Gate Information
- 🧳 Baggage Allowance
- ✅ Online Check-in
- 🎫 Booking Information
- ❌ Cancellation
- 💬 General Help

## 🧠 Technologies Used

- HTML5
- CSS3
- JavaScript
- Web Speech API
- Speech Recognition
- Speech Synthesis
- Lightweight NLP
- Entity Extraction

## 🔍 NLP Features

The assistant uses keyword-based intent classification to identify different user requests.

### Supported Intents

| Intent | Example Query |
|---|---|
| Flight Status | `What is the status of AI202?` |
| Gate Information | `Which gate is BA117?` |
| Baggage | `What is the baggage allowance?` |
| Check-in | `How do I check in?` |
| Booking | `I want to book a flight` |
| Cancellation | `I want to cancel my flight` |
| Help | `What can you do?` |

The system also extracts entities such as:

- Flight numbers
- City names

For example:

```text
Status of AI202
