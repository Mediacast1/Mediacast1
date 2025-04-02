# 🎙️ Mediacast1.ai

**AI-Powered Broadcasting Infrastructure for the Next Generation of Streamers, Podcasters, and Internet Broadcasters**

Mediacast1 is the spiritual successor of one of the earliest pioneers in internet streaming — reborn as **Mediacast1.ai**. This open-source broadcasting stack fuses classic Icecast2 technology with modern, AI-driven tools to deliver intelligent automation, seamless integrations, and scalable streaming solutions.

---

## 🌐 Live Project Website
👉 [https://mediacast1.ai](https://mediacast1.ai)  
🎧 Join our creator community: [CasterClub.com](https://casterclub.com)

---

## 🚀 Features

- 🎛 **PlaylistGen AI**  
  Generate curated playlists via text prompts, `.m3u`, `.pls`, `.json`, or YouTube links. Automatically tags tracks using smart metadata processors (ID3, filename parsing, and content heuristics).

- 📡 **CastIt Broadcasting Toolkit**  
  Web-based broadcasting and stream manager with support for:
  - AI-assisted scheduling
  - VJ/DJ rotation
  - Live override support
  - RTMP, HLS, Icecast2 outputs

- 🔁 **Simulcasting & External Push**  
  Integrations with YouTube, Twitch, Facebook Live, and custom RTMP endpoints.

- 🧠 **Auto-DJ / VJ Agent Modules**  
  AI microservices that curate, inject, and even announce content in real-time — powered by NLP and scheduling logic.

- ⚙️ **Custom Icecast2 Fork (in Go)**  
  A rewritten fork of Icecast2 focused on:
  - Modern protocols (HTTP/2+)
  - Cloud-native deployment (Docker/Kubernetes)
  - Authentication extensions (OAuth2, JWT)
  - Better scalability for pro-grade deployments

---

## 🧑‍💻 Tech Stack

- **Backend:** Go, Node.js, Python  
- **Frontend:** React (admin dashboard), Electron (desktop client), Tailwind CSS  
- **Streaming Tools:** FFmpeg, yt-dlp, Liquidsoap, ID3Lib  
- **Containerization:** Docker, Kubernetes-ready configs  
- **Storage:** S3-compatible object storage for media, Redis for queueing  
- **AI/ML Integration:** OpenAI, Whisper, Google Speech-to-Text (optional NLP modules)

---

## 📂 Repository Structure
```
/mediacast1/
├── playlistgen-ai/        # Prompt-based playlist generator
├── castit/                # Core broadcasting UI & backend
├── icecast-go/            # Custom Icecast2 fork in Golang
├── ai-agents/             # AutoDJ/VJ smart agents
├── utils/                 # Media processors, metadata tools
├── docker/                # Docker & Compose config
└── docs/                  # Project documentation
```
---

## 📦 Installation (Dev)

```bash
git clone https://github.com/Mediacast1/Mediacast1.git
cd Mediacast1
docker-compose up --build
```
Be sure to configure your .env file with API keys for AI services (optional), and stream ports.

⸻

📜 License

Mediacast1.ai is licensed under the MIT License.

⸻

💬 Community & Support
	•	Join the community on CasterClub
	•	Submit issues or feature requests via GitHub
	•	Follow updates and releases via @Mediacast1AI

⸻

🙌 Legacy Meets Future

Mediacast1.ai is more than a platform — it’s a tribute to the golden age of internet broadcasting, reimagined with modern technology, AI augmentation, and an open-source heart.

Welcome to the new frontier of streaming.

📡 Cast smarter. Broadcast better.
