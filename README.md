<div align="center">

<img src="https://media.giphy.com/media/U3qYN8S0j3bpK/giphy.gif" width="100%" height="40px" style="object-fit: cover;" />


# 🤖 WhatsApp AI Agent | n8n Automation

[![n8n](https://img.shields.io/badge/Orchestration-n8n-ff6b6b?style=for-the-badge\&logo=n8n)](https://n8n.io/)
[![OpenAI](https://img.shields.io/badge/AI-OpenAI_GPT--4o-412991?style=for-the-badge\&logo=openai)](https://openai.com/)
[![WhatsApp](https://img.shields.io/badge/Messaging-WhatsApp_Cloud_API-25D366?style=for-the-badge\&logo=whatsapp)](https://developers.facebook.com/docs/whatsapp)
[![Node.js](https://img.shields.io/badge/Runtime-Node.js-339933?style=for-the-badge\&logo=node.js)](https://nodejs.org/)

<p align="center">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&size=24&pause=1000&color=25D366&center=true&vCenter=true&width=700&lines=WhatsApp+AI+Agent+with+n8n;Sees+%7C+Listens+%7C+Speaks;Multimodal+AI+Automation" />
</p>

**A production-ready WhatsApp AI Agent that sees, listens, and speaks.**

<i>“Don’t just reply. Understand. Decide. Respond.”</i>

[View Demo](#) · [Report Bug](https://github.com/jeyaram1023/your-repo-name/issues) · [Request Feature](https://github.com/jeyaram1023/your-repo-name/issues)

</div>

---

<img src="https://media.giphy.com/media/hvRJCLFzcasrR4ia7z/giphy.gif" width="35" />

## 📖 Overview

This project showcases a **multimodal WhatsApp AI Agent** built using **n8n** and **OpenAI**. Unlike traditional chatbots limited to text, this agent understands **text messages, voice notes, and images**, reasons intelligently using GPT-4o, and responds via **text or synthesized voice**.

The system is designed to be **modular, scalable, and automation-first**, making it ideal for:

* Personal AI assistants
* Customer support automation
* Business messaging bots
* AI-powered workflow orchestration

---

<img src="https://media.giphy.com/media/3o7aD2saalBwwftBIY/giphy.gif" width="40" />

## ✨ Key Capabilities

* 📩 **Multimodal Input**: Text, Voice Notes, and Images
* 🧠 **AI Reasoning**: Context-aware responses using GPT-4o
* 🎤 **Speech-to-Text**: Audio transcription with OpenAI Whisper
* 🖼️ **Image Understanding**: Vision-based image analysis
* 🔊 **Text-to-Speech**: Voice replies for natural interaction
* 🔁 **End-to-End Automation**: Fully managed by n8n workflows

---

## 🆚 Problem vs Solution

| ❌ Traditional Bots     | ✅ WhatsApp AI Agent                    |
| ---------------------- | -------------------------------------- |
| Only text-based        | Supports text, audio & images          |
| No voice understanding | Transcribes & understands voice notes  |
| Cannot analyze images  | Uses AI vision for image understanding |
| Rule-based replies     | AI-driven decision making              |
| Limited scalability    | Modular & production-ready             |

---

<img src="https://media.giphy.com/media/l0HlBO7eyXzSZkJri/giphy.gif" width="80" />

## 🧩 Workflow Architecture

<p align="center">
  <img width="1150" alt="Workflow Architecture" src="https://github.com/user-attachments/assets/cee1a7d1-c501-4fc6-8550-92041757d42d" />
</p>

### 🔄 Intelligent Input Routing

1. **📝 Text Messages**

   * Sent directly to the AI Agent for reasoning and response generation.

2. **🎤 Voice Messages**

   * Audio downloaded from WhatsApp
   * Transcribed using **OpenAI Whisper**
   * Converted text passed to the AI Agent

3. **🖼️ Image Messages**

   * Image downloaded securely
   * Analyzed using **GPT-4o Vision**
   * Visual context forwarded to the AI Agent

The AI Agent then decides whether to respond via **text** or **audio**, ensuring a natural conversational experience.

---

<img src="https://media.giphy.com/media/QssGEmpkyEOhBCb7e1/giphy.gif" width="40" />

## 🛠️ Technology Stack

* **[n8n](https://n8n.io/)** – Workflow orchestration & automation engine
* **[WhatsApp Cloud API](https://developers.facebook.com/docs/whatsapp)** – Secure messaging interface
* **[OpenAI API](https://platform.openai.com/)**

  * GPT-4o – Reasoning & conversation
  * Whisper – Speech-to-text
  * Vision – Image analysis
  * TTS – Voice generation
* **[Node.js](https://nodejs.org/)** – Runtime environment

---

<img src="https://media.giphy.com/media/26BRuo6sLetdllPAQ/giphy.gif" width="40" />

## 🚀 Installation & Setup

<details>
<summary><b>🔻 Click to expand step-by-step setup</b></summary>

### 1️⃣ Install Node.js

Download and install Node.js (LTS recommended):
[https://nodejs.org/](https://nodejs.org/)

Verify installation:

```bash
node -v
npm -v
```

### 2️⃣ Install n8n

Install n8n globally:

```bash
npm install n8n -g
```

Start n8n:

```bash
n8n start
```

Open the editor:

```
http://localhost:5678
```

### 3️⃣ Import Workflow

1. Download the workflow JSON file from this repository
2. Open n8n Dashboard
3. Click **Import Workflow**
4. Upload the JSON file
5. Save and **Activate** the workflow

</details>

---

## 🔐 Environment Configuration

Create environment variables:

```env
OPENAI_API_KEY=your_openai_api_key
WHATSAPP_TOKEN=your_whatsapp_cloud_api_token
WHATSAPP_PHONE_NUMBER_ID=your_phone_number_id
VERIFY_TOKEN=your_custom_webhook_verify_token
```

⚠️ Keep these keys private and never commit them to GitHub.

---

## 🌐 Webhook Configuration

In your **Meta Developer Dashboard**:

* **Callback URL**
  `https://your-domain/webhook/whatsapp`

* **Verify Token**
  Must match `VERIFY_TOKEN`

---

<img src="https://media.giphy.com/media/l3vRfNA1p0rvhMSvS/giphy.gif" width="60" />

## 🧪 Testing the Agent

Try the following:

* **Text** → “Create a study schedule for me”
* **Voice** → Ask a question via voice note
* **Image** → Send a math problem or object photo

The agent will analyze the input and respond intelligently.

---

## 📬 Author & Contact

<div align="center">

**Jeyaram Reddy**

<a href="https://www.linkedin.com/in/jeyaram-ece-reddy">
  <img src="https://img.shields.io/badge/LinkedIn-Connect-0077B5?style=for-the-badge&logo=linkedin" />
</a>
<a href="mailto:jeyaram.reddy.ece@gmail.com">
  <img src="https://img.shields.io/badge/Email-Contact-D14836?style=for-the-badge&logo=gmail" />
</a>
<a href="https://jeyaram1023.github.io/My-portfolio/">
  <img src="https://img.shields.io/badge/Portfolio-Visit-2EA44F?style=for-the-badge&logo=google-chrome" />
</a>
<a href="https://github.com/jeyaram1023">
  <img src="https://img.shields.io/badge/GitHub-Follow-000000?style=for-the-badge&logo=github" />
</a>

</div>

---

<div align="center">

<img src="https://media.giphy.com/media/ZVik7pBtu9dNS/giphy.gif" width="80" />

⭐ <b>Star this repository if you find it useful!</b> ⭐

</div>

![Footer](https://capsule-render.vercel.app/api?type=waving\&color=0099ff\&height=100\&section=footer)
