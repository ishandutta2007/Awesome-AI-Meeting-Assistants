# 🎙️ Awesome-AI-Meeting-Assistants

## 🚀 Top AI Meeting Assistants Ecosystem

✨ **Curated List of SaaS Products & Open-Source GitHub Projects**  
🎯 *Focused on Real-Time Transcription, Local-First AI & Stealth Meeting Copilots*  
📅 **Last updated: October 2026**

This repository tracks notable **SaaS platforms** and **open-source projects** for **AI Meeting Assistants**. These tools enable professionals to capture meeting audio, generate real-time transcription, extract action items, and surface AI-suggested responses—increasingly with local-first architectures that keep sensitive conversations on-device.

💡 **Examples** include Otter.ai, Fireflies.ai, Fathom, Read AI, Sembly AI, Avoma, Jamie AI, Supernormal, MeetGeek, and tl;dv (the category leaders).

🔒 **Open-source emphasis**: This section is heavily expanded with every major active project for self-hosting, local Whisper transcription, and stealth overlay copilots—ideal for privacy-conscious professionals, neurodivergent users, and developers seeking transparent, vendor-independent meeting AI.

🤝 Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.

## 📑 Table of Contents

- [☁️ SaaS/Hosted Platforms](#saas-hosted-platforms)
- [💻 Open-Source GitHub Projects](#open-source-github-projects)
- [🤝 How to Contribute](#how-to-contribute)
- [⚠️ Disclaimer](#disclaimer)

<a id="saas-hosted-platforms"></a>
## ☁️ SaaS/Hosted Platforms

- 🦦 **[Otter.ai](https://otter.ai/)**  
  **The most widely adopted AI meeting assistant** with real-time transcription, automated summaries, and action item extraction. Integrates with Zoom, Google Meet, and Microsoft Teams. Free tier with limited minutes; Pro from ~$8.33/month.

- 🔥 **[Fireflies.ai](https://fireflies.ai/)**  
  AI notetaker with transcription, search, and analytics across meeting platforms. Features conversation intelligence, topic tracking, and CRM integration.

- 🌊 **[Fathom](https://fathom.video/)**  
  Free AI notetaker with unlimited recording and transcription. Features instant summaries, action items, and CRM sync. **The most generous free tier** in the category.

- 📊 **[Read AI](https://www.read.ai/)**  
  AI meeting assistant with engagement analytics, speaker coaching, and automated summaries. Features meeting health scores and attendance tracking.

- 📝 **[Sembly AI](https://www.sembly.ai/)**  
  AI meeting assistant with multi-language support, automated minutes, and task tracking.

- 📈 **[Avoma](https://www.avoma.com/)**  
  AI meeting assistant with revenue intelligence features. Features conversation analytics, coaching, and CRM integration.

- 🛡️ **[Jamie AI](https://www.meetjamie.ai/)**  
  **Privacy-focused AI notetaker** that runs locally without bots joining calls. Features on-device transcription and GDPR compliance.

- ⚡ **[Supernormal](https://supernormal.com/)**  
  AI meeting notes with templates, action items, and workflow automation.

- 🧠 **[MeetGeek](https://meetgeek.ai/)**  
  AI meeting assistant with recording, transcription, and highlights. Features team analytics and integrations.

- ⏱️ **[tl;dv](https://tldv.io/)**  
  AI meeting recorder with timestamps, highlights, and CRM sync. Free tier with unlimited recordings.

<a id="open-source-github-projects"></a>
## 💻 Open-Source GitHub Projects

- 🥷 **[Natively (natively-cluely-ai-assistant)](https://github.com/Natively-AI-assistant/natively-cluely-ai-assistant)**  
  **The most feature-complete open-source meeting assistant and interview copilot** (open-source). **The leading Cluely alternative with local-first architecture.** Features **Auto Answer (Beta)** — answers appear automatically when the other person finishes a question, with intelligent silence when no answer is wanted . **New answer engine** picks source properly (résumé, uploaded document, live conversation, or general knowledge) with follow-up memory . **Rebuilt meeting notes** with adaptive summaries, editable speaker labels, and follow-up email drafts . **Built-in Modes** including Call Center mode. **Skills** — upload custom skills as files or folders . **NVIDIA NIM** speech-to-text with nine streaming models . **Role Insight (Pro)** — paste job description, see requirements scored against profile . **Redesigned meeting overlay** with streaming answers and jump-to-latest . **Windows stealth typing** — type in overlay without losing call focus . **LiteLLM model picker** with configurable defaults . **Chrome companion extension** — press ⌘/Ctrl+Y to pull page content into answers . **Cross-platform**: macOS (signed) and Windows (unsigned, SmartScreen warning expected) .

- ⚡ **[Pika (pikabaka)](https://github.com/royisme/pikabaka)**  
  **Open-source AI interview copilot & meeting assistant** (AGPL-3.0) . **Sub-500ms transcription** powered by Rust native audio module (cpal + WebRTC VAD + rubato resampling) . **Dual-channel capture** — system audio and microphone streamed independently for clean attribution . **Any LLM, any STT** — switch providers at runtime: OpenAI, Anthropic Claude, Google Gemini, Groq, Ollama, or any OpenAI-compatible endpoint . **Local RAG memory** — past meetings indexed with `sqlite-vec` for on-device search . **Screenshot reasoning** — capture screen or region, pipe to vision model . **Stealth overlay** — disguise process name, hide from screen-sharing . **Cross-platform**: macOS (Apple Silicon + Intel) and Windows 10/11 .

- 🕊️ **[Freely](https://www.npmjs.com/package/freely)**  
  **Your AI screen assistant — local, private, free** (open-source, NPM) . **The open-source alternative to Cluely** — "Cluely charges $150/month. Freely runs on your machine, uses your own API key, and costs pennies" . **Real-time transcription** via local Whisper STT — no cloud dependency for speech-to-text . **Multi-provider AI** — Gemini, Anthropic (Claude), OpenAI . **Screen capture exclusion** — overlay excluded from screenshots and recordings (Windows) . **Background context injection** — drop CV or background info for tailored responses . **Voice-triggered responses** — two-second pause triggers AI suggestion . **Dual-window overlay** — floating bar for responses, side panel for transcript . **Hotkey / CLI triggers** — `freely ask`, `freely screenshot` . **Privacy-first** — no account, no cloud sync, no audio leaves machine (unless cloud LLM used) . **Cross-platform**: Linux (primary), Windows (less tested) .

- 💎 **[Prismical (amicalhq)](https://github.com/amicalhq/prismical)**  
  **Open-source AI note taker — transcribe meetings, lectures, and voice notes** (MIT) . **Local-first AI** — on-device transcription with whisper.cpp . **Real-time meeting transcription** — system audio capture, no bot joins call . **AI summaries & action items** — structured notes with key decisions and follow-ups . **Voice notes** — talk or type, AI structures thoughts . **AI skills** — Enhance, Cleanup, Ask across notes, or write custom skills . **Bring your own model** — OpenAI, Anthropic, OpenRouter, any OpenAI-compatible endpoint, or local Ollama . **Meeting detection** — notices when meeting app starts using microphone . **Floating widget** — always-on-top compact window for live transcripts . **Full-text search** across all meetings and notes . **MCP server** — connect notes to Claude, ChatGPT, Gemini . **Cross-platform**: macOS (Apple silicon + Intel) and Windows (x64) .

- 🤝 **[MeetingBro](https://github.com/armpro24-blip/MeetingBro)**  
  **Open-source, local-first AI meeting assistant** (open-source) . **Real-time transcription, translation & live summaries** . **No platform plugin needed** — captures system audio directly . **Three performance modes**: Summary only (lower-end machines), Balanced (most users), Performance (stronger CPUs/GPUs) . **Language support**: Auto (multilingual), English, Chinese, German . **Cross-platform**: Windows, macOS, Linux .

- 🐝 **[bee-recorder](https://pypi.org/project/bee-recorder/)**  
  **Privacy-first meeting recorder with local transcription and diarization** (open-source, PyPI) . **Nothing ever leaves the machine** with local diarization mode . **Whisper transcription** (mic + system audio) with **SpeechBrain diarization** . **Merging** — mic speakers become `Mic_XX`, remote participants become `Speaker_XX` . **Device change handling** — follows device changes during call, stitches onto single timeline . **Speaker labeling** — assign real names after processing . **Output**: mic.wav, system.wav, metadata.json, JSON and Markdown transcripts . **Performance**: ~3.7× real time per channel on 20-thread CPU (1-hour meeting = ~30 minutes end-to-end) .

- 🔌 **[Meeting MCP Server (workos-meeting-mcp-server)](https://pypi.org/project/workos-meeting-mcp-server/)**  
  **Independent MCP server for meeting transcription and analysis** (MIT, PyPI) . **100% local** — all transcription runs locally on CPU, no data leaves machine . **Audio transcription** — MP3, WAV, M4A, OGG, FLAC, AAC, WMA via faster-whisper . **Video support** — MP4, WebM, MKV, MOV, AVI via ffmpeg . **Meeting insights** — structured data: summary, key decisions, action items, sentiment . **Meeting notes** — formatted markdown . **Follow-up email** — professional drafts . **Available tools**: `meeting_transcribe_audio`, `meeting_extract_insights`, `meeting_generate_notes`, `meeting_draft_follow_up` . **Integrates with**: Claude Desktop, Cursor, Windsurf, WorkOS .

- ⚡ **[Pika (royisme/pikabaka)](https://github.com/royisme/pikabaka)**  
  See Pika above.

- 🪟 **[IA-notetaking (Igor-C-Assuncao)](https://github.com/Igor-C-Assuncao/IA-notetaking)**  
  **Privacy-first AI meeting assistant as floating widget** (open-source) . **Powered by Tauri v2, WhisperX, and LangGraph** . **No bots, no meeting links** — records microphone and system audio natively . **BYOK system** — `OllamaStrategy`, `OpenAIStrategy`, `GeminiStrategy`, `AnthropicStrategy` share common `LLMProvider` interface . **Cross-platform audio capture** — `WindowsAudioCapture`, `MacosAudioCapture`, `LinuxAudioCapture` via Factory Method . **Pipeline**: Audio Mixer → Silero VAD → WhisperX → LangGraph Agent .

- 🥧 **[pi-notetaker (@dvrosalesm)](https://www.npmjs.com/package/@dvrosalesm/pi-notetaker)**  
  **Meeting notes extension for cmd0 desktop agent** (open-source, NPM) . **Record audio, transcribe locally with Whisper, generate structured summaries** . **All offline, all local** . **Commands**: `/meeting start`, `/meeting stop`, `/meeting list`, `/meeting view`, `/meeting transcript` . **LLM-callable tools** for conversational meeting management . **Platforms**: macOS and Linux. Windows not supported .

- 🖥️ **[meeting-cli (@gabrielcraveiro)](https://www.npmjs.com/package/@gabrielcraveiro/meeting-cli)**  
  **CLI tool capturing system audio + microphone, transcribing with AI, generating structured notes** (open-source, NPM) . **Built for WSL2 + Windows environments** with Obsidian vault integration . **WASAPI audio capture** — records system audio and microphone simultaneously . **Live transcription** — 45-second segments via Deepgram . **AI-powered summaries** — participants, decisions, action items . **Live chat during recording** . **Auto-insights** every 3 minutes . **Smart template detection** — daily, 1on1, retro, planning, technical . **Silence detection** — auto-stops after 3 minutes .

- ☁️ **[ai-meeting-saas (vivekkushalch)](https://github.com/vivekkushalch/ai-meeting-saas)**  
  **AI Online Meeting Transcribe, Summary, Keypoints Action Items** (open-source) . **Microservices architecture** — Next.js 16 frontend, FastAPI gateway, Python Celery worker . **Audio never passes through gateway** — presigned URLs upload directly to MinIO . **Signed worker callback** — HMAC-SHA256 with timestamp and replay window . **Processing**: WhisperX + pyannote for transcription and diarization, Gemini for analysis . **Private by design** — audio lives in own S3-compatible storage .

<a id="additional-strong-open-source-options"></a>
### 🔍 Additional Strong Open-Source Options

- ⚖️ **[Pika Alternatives Comparison](https://github.com/royisme/pikabaka)** — Pika README includes comparison table: Pika (AGPL-3.0, BYO key, offline Ollama, real-time answers, stealth overlay, local RAG, custom shortcuts) vs Cluely (proprietary) vs Granola vs Otter .
- ⚖️ **[Natively vs Freely Comparison](https://github.com/Natively-AI-assistant/natively-cluely-ai-assistant)** — Natively offers Auto Answer, NVIDIA NIM, Chrome companion, Call Center mode . Freely offers local Whisper, multi-provider AI, screen capture exclusion .
- 🎙️ **[Whisper Model Comparison](https://pypi.org/project/workos-meeting-mcp-server/)** — tiny (75MB, ~1GB VRAM, ~32x speed), base (142MB), small (466MB, ~2GB VRAM, ~6x, recommended), medium (1.5GB, ~5GB VRAM, ~2x), large-v3 (3GB, ~10GB VRAM, ~1x, best accuracy) .
- 🔄 Community **n8n** workflows for meeting transcript processing and action item routing.

🛠️ **Frameworks for building custom systems**: Combine **Natively** for full-featured stealth copilot with **Pika** for sub-500ms transcription and local RAG, **Prismical** for cross-platform note-taking with MCP integration, **Meeting MCP Server** for local MCP-based transcription, and **Whisper** for local speech-to-text—creating a fully self-hosted, private AI meeting assistant stack.

<a id="how-to-contribute"></a>
## 🤝 How to Contribute

1. 🍴 Fork the repo.
2. 📝 Add/edit entries in `README.md` (follow existing format).
3. 🔍 Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.
4. 🚀 Submit PR with a short explanation.

⭐ Star the repo if you find it useful!

<a id="disclaimer"></a>
## ⚠️ Disclaimer

- 🌐 This is a **community-curated** list — not exhaustive and not an endorsement.
- ⚖️ AI meeting assistants capturing audio must comply with **wiretapping laws, consent requirements, and data protection regulations** (GDPR, CCPA, etc.). **Always obtain consent before recording meetings.**
- 🚀 **Open-source meeting assistants are mature and production-ready.** Natively provides the most feature-complete stealth copilot with Auto Answer, NVIDIA NIM, and Chrome companion . Pika delivers sub-500ms transcription with local RAG memory . Freely runs entirely locally with no account required . **These are genuine alternatives to Cluely and Otter.ai.**
- 🔍 **Cluely's credibility issues are well-documented.** The company's $7M ARR claim was admitted to be false (real number $5.2M) . A mid-2025 data breach exposed data on **83,000+ users** including interview transcripts and screenshots . **Independent testing revealed response delays of 5-90 seconds and hallucinations** . The company has repositioned from "cheat on everything" to conventional meeting assistant .
- 🛑 **Stealth modes carry ethical and legal risk.** Natively, Pika, and Freely all offer screen-share invisibility . **Using these tools to deceive interviewers, clients, or colleagues may violate terms of service, employment agreements, and professional ethics standards.** These tools are legitimate for accessibility, interview practice, and personal note-taking—not for deception.
- 🔒 **Local-first architecture is the privacy advantage.** Freely, Prismical, bee-recorder, and Meeting MCP Server all run transcription locally with no cloud dependency . **Audio never leaves the device** when using local STT and Ollama. This is critical for confidential business discussions and regulated industries.
- ⚙️ Self-hosted open-source solutions require proper GPU provisioning for local Whisper models, audio device configuration, and ongoing maintenance. **Consent and compliance are the user's responsibility**—tools provide capture, not legal authorization.

---

🌟 **Made for professionals, interview candidates, and developers building transparent meeting AI solutions.**  
✨ Let's make AI Meeting Assistants more open, data-driven, and privacy-preserving.
