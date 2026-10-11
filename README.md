<p align="center">
  <a href="https://github.com/Mr5elfDe5truct/prestige">
    <img src="https://raw.githubusercontent.com/Mr5elfDe5truct/prestige/main/docs/banner.png" alt="Prestige by R.G. Studios: Creating the world around you" width="100%">
  </a>
</p>

## 🎩 Hi, I'm Ryan B. Gyles

I build **Prestige by R.G. Studios**, a desktop AI that chats, talks back, sees through your webcam and makes images, video and songs,
running entirely on your own PC. I believe powerful AI should be **free, private and yours**: no accounts, no cloud, no subscriptions.

<p align="center">
  <a href="https://github.com/Mr5elfDe5truct/prestige/releases/latest"><img alt="Download Prestige" src="https://img.shields.io/github/v/release/Mr5elfDe5truct/prestige?style=for-the-badge&color=d6202b&label=download%20prestige"></a>
  <a href="https://github.com/Mr5elfDe5truct/prestige"><img alt="Prestige on GitHub" src="https://img.shields.io/badge/source-Mr5elfDe5truct%2Fprestige-d9a441?style=for-the-badge&logo=github"></a>
  <img alt="100% local" src="https://img.shields.io/badge/100%25%20local-offline-1a1111?style=for-the-badge&labelColor=d6202b">
  <a href="https://github.com/sponsors/Mr5elfDe5truct"><img alt="Sponsor" src="https://img.shields.io/badge/sponsor-%E2%9D%A4-ea4aaa?style=for-the-badge&logo=githubsponsors&logoColor=white"></a>
</p>

## ✨ What Prestige does

| | |
|---|---|
| 💬 **Chat with any local model** | Ollama and llama.cpp models, tools, web search, shared long-term memory and searchable past chats |
| 📞 **Live calls** | Hands-free voice and webcam calls: just talk, interrupt any time, cloned voices included |
| 🖼️ **Images and video** | Qwen-Image, Z-Image, LTX and Wan 2.2 long video, with reference images, edit by instruction, paint to change and click to select |
| 🎵 **Songs and music videos** | ACE-Step songs with a full song editor, and Storyboard music videos planned shot by shot |
| 🔬 **Deep Research** | Plans searches, reads the web and writes a cited report |
| 📚 **Chat with your files** | PDFs, Word docs and notes, answered with page citations, all on your PC |
| 🎭 **Characters** | Personas with their own voice, face and memory |
| 🎮 **Canvas** | Ask for a game, a chart or a 3D scene and play it right beside the chat |
| 📱 **Phone access + Android app** | Talk to your PC's AI from your phone, camera and all |
| 🎨 **Make it yours** | Eleven styles, seven themes, custom colours, and a top hat whose mustache talks |
| 📦 **Set up in one go** | Setup installs the AI engines and models for you; Packs adds or removes models any time |
| ⚡ **Built for real hardware** | Tuned for a 12 GB RTX 3060, splits big models across two GPUs, updates itself |

<table>
  <tr>
    <td width="50%"><img src="https://raw.githubusercontent.com/Mr5elfDe5truct/prestige/main/docs/chat.jpg" alt="Prestige chat"><br><p align="center"><b>Chat</b></p></td>
    <td width="50%"><img src="https://raw.githubusercontent.com/Mr5elfDe5truct/prestige/main/docs/studio.jpg" alt="Prestige Studio gallery"><br><p align="center"><b>Studio</b></p></td>
  </tr>
  <tr>
    <td><img src="https://raw.githubusercontent.com/Mr5elfDe5truct/prestige/main/docs/highlights/storyboard.jpg" alt="Storyboard: a song and every shot planned"></td>
    <td><img src="https://raw.githubusercontent.com/Mr5elfDe5truct/prestige/main/docs/highlights/deep-research.jpg" alt="Deep Research: a cited report from the web"></td>
  </tr>
  <tr>
    <td><img src="https://raw.githubusercontent.com/Mr5elfDe5truct/prestige/main/docs/highlights/click-to-select.jpg" alt="Click to select: one click outlines it"></td>
    <td><img src="https://raw.githubusercontent.com/Mr5elfDe5truct/prestige/main/docs/highlights/styles.jpg" alt="Eleven styles"></td>
  </tr>
  <tr>
    <td><img src="https://raw.githubusercontent.com/Mr5elfDe5truct/prestige/main/docs/highlights/setup.jpg" alt="Sets itself up: one installer"></td>
    <td><img src="https://raw.githubusercontent.com/Mr5elfDe5truct/prestige/main/docs/highlights/memory.jpg" alt="Remembers you: memory kept on your PC"></td>
  </tr>
  <tr>
    <td><img src="https://raw.githubusercontent.com/Mr5elfDe5truct/prestige/main/docs/dragon.jpg" alt="A red and gold dragon rendered in Prestige"><br><p align="center"><b>Made in Prestige</b></p></td>
    <td><img src="https://raw.githubusercontent.com/Mr5elfDe5truct/prestige/main/docs/animate-dragon.gif" alt="The dragon render animated with Wan 2.2"><br><p align="center"><b>...and brought to life</b></p></td>
  </tr>
</table>

## 🛠️ Under the hood

Prestige is one installer: its **Setup** installs the local AI engine it drives (Ollama, llama.cpp, ComfyUI, Whisper, Kokoro,
VoxCPM2 and a tool server) with the model packs you pick, and Prestige starts, stops and updates it all itself. The engine
used to be its own project, Custom AI Workstation; it now lives inside Prestige. Built with Tauri 2, Rust and TypeScript.

<p>
  <img alt="Tauri" src="https://img.shields.io/badge/Tauri-2-24C8DB?style=flat-square&logo=tauri&logoColor=white">
  <img alt="Rust" src="https://img.shields.io/badge/Rust-CE422B?style=flat-square&logo=rust&logoColor=white">
  <img alt="TypeScript" src="https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white">
  <img alt="Python" src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white">
  <img alt="PowerShell" src="https://img.shields.io/badge/PowerShell-5391FE?style=flat-square&logo=powershell&logoColor=white">
  <img alt="Ollama" src="https://img.shields.io/badge/Ollama-0f0a0a?style=flat-square&logo=ollama">
  <img alt="ComfyUI" src="https://img.shields.io/badge/ComfyUI-0f0a0a?style=flat-square">
  <img alt="Windows 11" src="https://img.shields.io/badge/Windows%2011-0078D4?style=flat-square&logo=windows11&logoColor=white">
</p>

Windows 11 today; Linux and macOS are next.

## 💖 Support

Everything I make is free and open source. If Prestige saves you a subscription, you can help fund what comes next on
[GitHub Sponsors](https://github.com/sponsors/Mr5elfDe5truct).

<p align="center"><sub>R.G. Studios · <i>Creating the world around you</i></sub></p>
