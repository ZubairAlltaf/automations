# 🎬 AI-Powered Short Form Video Generator (n8n Workflow)

This is a fully automated **AI-based video generation workflow** built in [n8n](https://n8n.io), allowing you to create complete **short-form videos from a single prompt**. No need to manually switch between image tools, animation tools, voice-over generators, or spreadsheets. Just **enter your idea**, and let the automation handle the rest.

---

## ⚡ Features

- 🖼️ **Image Generation** using `Qubico/flux1-dev` from PIAPI
- 🎞️ **Image to Video** transformation via Kling API
- 🗣️ **Voiceover Creation** using PIAPI voice models
- 📊 **Google Sheets Integration** for prompt input/output tracking
- 📺 **YouTube API Integration** (optional) for direct publishing

---

## 🧠 How It Works

1. You input a prompt.
2. PIAPI generates a stunning vertical image.
3. Kling converts it into an animated video.
4. Voice-over is created based on your prompt’s vibe.
5. Google Sheets tracks all steps and stores links.
6. (Optional) Automatically publish on YouTube.

---

## 🔗 Required Credentials

- PIAPI API Key (Free tier supported)
- Kling API Key (Get from piapi.ai)
- Google Sheets credentials (OAuth2)
- YouTube API (Enable via Google Cloud Console)

---

## 🧾 Required Google Sheets Format

To prevent errors, structure your sheet as shown below:  
📄 [View Google Sheet Template](https://docs.google.com/spreadsheets/d/1DL1pkllGIc6rushUOdfHGHS_Q7d91PyxSofUoLE5FH8/edit?usp=sharing)

---

## 🚀 Getting Started

1. Fork or clone this repo.
2. Import the `.json` workflow into your n8n instance.
3. Add all required credentials.
4. Start creating short-form videos with a single idea!

---

## 👨‍💻 Author

**Zubair Alltaf**  
🔗 GitHub: [github.com/ZubairAlltaf](https://github.com/ZubairAlltaf)

---
