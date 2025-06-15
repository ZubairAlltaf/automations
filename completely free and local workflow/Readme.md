 🎬 Free & Local Short-Form Video Content Generator (n8n + Python + Docker)

This is a **fully free**, local, and open-source automation workflow designed to generate complete short-form video content (YouTube Shorts, Reels, TikToks) **using only a single topic prompt** — no API credits needed!

Perfect for learning AI automation and how to connect **open LLMs, image & video generation tools, and voice synthesis** into a powerful automated pipeline, all hosted locally.

---

## 🚀 What This Workflow Does

With just a **simple topic**, this system automatically:

- 🧠 Writes a **script** using OpenRouter LLM (e.g., `Qwen`)
- 🔊 Converts it to **voice-over audio** (TTS via local Python)
- ✍️ Generates **captions (SRT)** locally
- 🖼️ Creates **AI images** and 🎞️ **AI videos**
- 🎥 Downloads **stock video clips** from Pexels
- 📂 Saves all assets (scripts, images, videos, audio, captions) in a dedicated folder

> ⚡️ This is **offline-first**: All heavy lifting is done using **your own machine** (Python + Docker). You own the full pipeline.

---

## 🧠 Learnings & Tech Used

- How to run **open-source LLMs** using OpenRouter for scripting & visual prompts
- Running **local Python TTS & Captioning services**
- How to let Docker interact with **local Python scripts** using `host.docker.internal`
- Using **n8n** for connecting services and orchestrating automation
- File handling, formatting, and result storage inside **Docker-mounted folders**

---

## 📦 Requirements

1. ✅ **VS Code** to run Python scripts
2. ✅ **Python 3.10+** (install globally)
3. ✅ **Docker Desktop**
4. ✅ **n8n** (locally or via Docker)
5. ✅ Local versions of:
   - `generate_script.py` (OpenRouter-based script generation)
   - `create_video.py` (generates image, video, and stores outputs)

---

## ⚙️ Setup Instructions

1. **Run Python Scripts (In VS Code Terminal)**

```bash
python generate_script.py
python create_video.py
🔒 Do NOT modify any line or port number in these files — changes can break the workflow!

Start Docker Desktop

Make sure Docker is running. It mounts a /files directory to store all generated outputs.

Import the Workflow in n8n

Go to your n8n instance

Click Import Workflow and select the .json file

Configure Localhost Access

Ensure your Docker container can reach your local Python server using:

http://host.docker.internal:<port>

🧪 How to Use
Trigger the workflow using a Form Trigger or manual input

Enter a topic (e.g., “How AI is changing music”)

Workflow generates:

✅ script.txt

✅ audio.wav

✅ subtitles.srt

✅ image.png

✅ video.mp4

✅ stock_clip.mp4

All files are saved to a unique /files/execution-id/ folder on your Docker volume

🗂 Example Google Sheet (Optional Input Source)
You can also use a structured Google Sheet like this to drive inputs:
📎 View Sheet Template

📍 Notes
✅ Ideal for local learning & experimentation

🛠️ Created with free tools only — no paid APIs needed

📁 Each run saves outputs in new folders for clean separation

🚫 Avoid changing ports or script logic unless you know what you're doing

📶 Works best on Windows/Mac using Docker Desktop + VS Code

👨‍💻 Author
Zubair Alltaf
🌐 GitHub: github.com/ZubairAlltaf

🎓 This project is for educational purposes. It's a fully local, open-source way to understand the behind-the-scenes of modern AI content automation tools.

Copy
Edit

---

Would you also like:

- A `.json` template to go with it?
- A separate visual `diagram.png` for explaining the flow?
- A badge or status display for GitHub (e.g., `Made with n8n`, `Built Locally`, `100% Free Tools`)?