### Hi this is Tianle (DDX) 😄

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=flat&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/dai-t-11b6b0137/) [![X (Twitter)](https://img.shields.io/badge/X-000000?style=flat&logo=x&logoColor=white)](https://x.com/ddx0510) [![Discord](https://img.shields.io/badge/Discord-5865F2?style=flat&logo=discord&logoColor=white)](https://discord.com/users/809306588267282433)


- Computer Science graduate from the National University of Singapore (Software development + game development)
- Fullstack Software Developer at [Platox.AI](https://www.ccmonet.ai/)
- Part-time Game Developer with [Turbo](https://turbo.computer/)

**Tech Stack:**

<table>
<tr>
<td><strong>💻 Frontend</strong></td>
<td>
<img src="https://img.shields.io/badge/React-20232A?style=flat&logo=react&logoColor=61DAFB" alt="React" />
<img src="https://img.shields.io/badge/Vue.js-35495E?style=flat&logo=vue.js&logoColor=4FC08D" alt="Vue.js" />
<img src="https://img.shields.io/badge/Next.js-000000?style=flat&logo=next.js&logoColor=white" alt="Next.js" />
<img src="https://img.shields.io/badge/TypeScript-007ACC?style=flat&logo=typescript&logoColor=white" alt="TypeScript" />
<img src="https://img.shields.io/badge/Tailwind_CSS-38B2AC?style=flat&logo=tailwind-css&logoColor=white" alt="Tailwind CSS" />
<img src="https://img.shields.io/badge/Flutter-02569B?style=flat&logo=flutter&logoColor=white" alt="Flutter" />
<img src="https://img.shields.io/badge/Figma-F24E1E?style=flat&logo=figma&logoColor=white" alt="Figma" />
</td>
</tr>
<tr>
<td><strong>⚙️ Backend</strong></td>
<td>
<img src="https://img.shields.io/badge/Go-00ADD8?style=flat&logo=go&logoColor=white" alt="Go" />
<img src="https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white" alt="Python" />
<img src="https://img.shields.io/badge/Java-ED8B00?style=flat&logo=openjdk&logoColor=white" alt="Java" />
<img src="https://img.shields.io/badge/C++-00599C?style=flat&logo=c%2B%2B&logoColor=white" alt="C++" />
<img src="https://img.shields.io/badge/Flask-000000?style=flat&logo=flask&logoColor=white" alt="Flask" />
<img src="https://img.shields.io/badge/Redis-DC382D?style=flat&logo=redis&logoColor=white" alt="Redis" />
<img src="https://img.shields.io/badge/Nginx-009639?style=flat&logo=nginx&logoColor=white" alt="Nginx" />
</td>
</tr>
<tr>
<td><strong>☁️ Cloud & DevOps</strong></td>
<td>
<img src="https://img.shields.io/badge/AWS-232F3E?style=flat&logo=amazon-aws&logoColor=white" alt="AWS" />
<img src="https://img.shields.io/badge/Google_Cloud-4285F4?style=flat&logo=google-cloud&logoColor=white" alt="Google Cloud" />
<img src="https://img.shields.io/badge/Kubernetes-326CE5?style=flat&logo=kubernetes&logoColor=white" alt="Kubernetes" />
<img src="https://img.shields.io/badge/Docker-2496ED?style=flat&logo=docker&logoColor=white" alt="Docker" />
<img src="https://img.shields.io/badge/Firebase-FFCA28?style=flat&logo=firebase&logoColor=black" alt="Firebase" />
<img src="https://img.shields.io/badge/Git-F05032?style=flat&logo=git&logoColor=white" alt="Git" />
</td>
</tr>
<tr>
<td><strong>🎮 Game Dev</strong></td>
<td>
<img src="https://img.shields.io/badge/Turbo-FF6B6B?style=flat" alt="Turbo" />
<img src="https://img.shields.io/badge/Unity-000000?style=flat&logo=unity&logoColor=white" alt="Unity" />
<img src="https://img.shields.io/badge/Godot-478CBF?style=flat&logo=godot-engine&logoColor=white" alt="Godot" />
<img src="https://img.shields.io/badge/Unreal_Engine-313131?style=flat&logo=unreal-engine&logoColor=white" alt="Unreal Engine" />
<img src="https://img.shields.io/badge/C%23-239120?style=flat&logo=c-sharp&logoColor=white" alt="C#" />
<img src="https://img.shields.io/badge/C++-00599C?style=flat&logo=c%2B%2B&logoColor=white" alt="C++" />
</td>
</tr>
</table>

---

## 🚀 Software Projects

### 🤖 nanobot-go - Lightweight Concurrent Team Agent

<table>
<tr>
<td width="50%" valign="top">

#### Architecture

```mermaid
graph TB
    subgraph Channels
        CLI[CLI]
        Lark[Lark]
    end
    subgraph Agent
        RUN[Router] --> WA[Worker A]
        RUN --> WB[Worker B]
    end
    CLI & Lark --> RUN
    WA & WB --> LLM[12+ LLM Providers]
    WA & WB --> TOOLS[10+ Tools + MCP]
```

</td>
<td width="50%" valign="top">

**A lightweight, concurrent team agent built in Go.** Inspired by [nanobot](https://github.com/HKUDS/nanobot).

~5,000 lines of Go. Single binary. No runtime dependencies. Built for the [CCMonet](https://ccmonet.dev) team.

**Features:**
- 🔀 **Concurrent Sessions**: Per-session goroutines with FIFO queuing
- 🧠 **LLM-Powered Memory**: Auto-consolidation into persistent knowledge base
- 🔧 **10+ Tools + MCP**: File ops, shell, web, API queries, sub-agents, cron
- 🔌 **12+ Providers**: Auto-detection from API key (OpenRouter, Gemini, Claude, etc.)
- 📋 **Markdown Skills**: Add capabilities without code changes
- 💬 **Multi-Channel**: CLI + Lark (Feishu) with @mention support

**Tech Stack:** Go | Cobra | robfig/cron | MCP Protocol

[**📂 View on GitHub**](https://github.com/ddx-510/nano-bot-go)

</td>
</tr>
</table>

### 🏢 OpenCode Pixel Office - AI Agent Visualizer

<table>
<tr>
<td width="50%" valign="top">

#### 📸 Screenshots

<img src="https://private-user-images.githubusercontent.com/20592322/544933540-e20e2e68-a032-4747-a027-aacca0f274e5.png?jwt=eyJ0eXAiOiJKV1QiLCJhbGciOiJIUzI1NiJ9.eyJpc3MiOiJnaXRodWIuY29tIiwiYXVkIjoicmF3LmdpdGh1YnVzZXJjb250ZW50LmNvbSIsImtleSI6ImtleTUiLCJleHAiOjE3NzI0MjA3NTgsIm5iZiI6MTc3MjQyMDQ1OCwicGF0aCI6Ii8yMDU5MjMyMi81NDQ5MzM1NDAtZTIwZTJlNjgtYTAzMi00NzQ3LWEwMjctYWFjY2EwZjI3NGU1LnBuZz9YLUFtei1BbGdvcml0aG09QVdTNC1ITUFDLVNIQTI1NiZYLUFtei1DcmVkZW50aWFsPUFLSUFWQ09EWUxTQTUzUFFLNFpBJTJGMjAyNjAzMDIlMkZ1cy1lYXN0LTElMkZzMyUyRmF3czRfcmVxdWVzdCZYLUFtei1EYXRlPTIwMjYwMzAyVDAzMDA1OFomWC1BbXotRXhwaXJlcz0zMDAmWC1BbXotU2lnbmF0dXJlPTU5MjliZmJjYWNlNzZjZDFlNDM3ODRhYjhhZjhhNGUwMGZiZTQ5Y2Y2YmQ0NDA5ZjkwNjRkZDY0ZDdhYWEzNDImWC1BbXotU2lnbmVkSGVhZGVycz1ob3N0In0.PNyYoCYuOTunhXEyajouW2Neorjmb7QgOnqCPV7qCt0" alt="Pixel Office" />

</td>
<td width="50%" valign="top">

**Watch your AI coding agents work in a retro pixel-art office!**

An OpenCode plugin that visualizes AI agent activity through a pixel-art office dashboard. Supports both OpenCode and Claude Code CLI with live WebSocket updates.

**Features:**
- 🎮 **Pixel Art Visualization**: Retro office showing agents working in real-time
- 🔀 **Dual CLI Support**: Works with OpenCode and Claude Code
- 📡 **Live WebSocket Updates**: Real-time agent activity streaming
- 📱 **Mobile-Responsive**: QR code connectivity for mobile viewing
- 🗂️ **Multi-Session Tracking**: Monitor agents across repositories

**Tech Stack:** React | PixiJS | Express.js | WebSocket | TypeScript

[**📂 View on GitHub**](https://github.com/ddx-510/opencode-pixel-office) | [**📦 npm**](https://www.npmjs.com/package/opencode-pixel-office)

</td>
</tr>
</table>

### 🖼️ React Multi Crop Image

<table>
<tr>
<td width="50%" valign="top">

#### 📸 Demo

<img src="https://github.com/ddx-510/react-multi-crop-image/blob/main/20250115162853_rec_.gif?raw=true" alt="React Multi Crop Image Demo" />

</td>
<td width="50%" valign="top">

**A React component for drawing multiple crop regions on a single image.**

Originally built for document processing and receipt scanning at [cc:Monet](https://ccmonet.ai). Draw, resize, and export multiple crop areas as base64 — perfect for OCR, document processing, and image annotation workflows.

**Features:**
- ✂️ **Multi-Crop**: Draw and manage multiple crop regions on one image
- 📤 **Base64 Export**: Export cropped sections as data URLs
- 🎨 **Fully Customizable**: Style crop regions, icons, and interactions
- 📜 **Scroll-Aware**: Handles scrollable containers and hi-res images
- 🔷 **TypeScript**: Full type support

**Tech Stack:** React | TypeScript | Lodash

```bash
npm install react-multi-crop-image
```

[**📂 View on GitHub**](https://github.com/ddx-510/react-multi-crop-image) | [**📦 npm**](https://www.npmjs.com/package/react-multi-crop-image)

</td>
</tr>
</table>

### 📦 ddSideBar - Arc-Style Sidebar for Chrome

<table>
<tr>
<td width="50%" valign="top">

#### 📸 Screenshots

[<img src="https://lh3.googleusercontent.com/tK9GLRJ2dQwB9jiJrs48aJOs-PXDKeJ9q2GHwOrwd0KdjLYrSoxjQ2BfQG3yxIwRenRND8hqrL4v0GfUviW-tbwYtg=s1600-w1600-h1000" />](https://chromewebstore.google.com/detail/echdjophnbkljbokigbpknajhbjngeic)

</td>
<td width="50%" valign="top">

**Arc-Style Sidebar Extension** - Bring Arc browser's elegant sidebar experience to Chrome!

A Chrome extension that brings Arc browser's innovative tab and space management to Chrome. Organize your browsing with a beautiful, minimalist sidebar that puts your tabs and bookmarks at your fingertips.

**Features:**
- 🎨 **Arc-Style Sidebar**: Beautiful left sidebar with tabs list and glassmorphism effects
- 📑 **Tabs Management**: Quick tab switching, closing, and organization
- 🗂️ **Spaces Organization**: Create multiple spaces with custom names, icons, and colors
- 🔖 **Bookmarks Integration**: Two-layer system for bookmarks and tabs
- ⚙️ **Dual Mode Support**: Choose between Iframe injection or Chrome SidePanel
- 🔒 **Privacy First**: All data stored locally, nothing transmitted to external servers

**Tech Stack:** Chrome Extension Manifest V3 | Vanilla JavaScript | Modern CSS | Chrome APIs

[**📥 Install from Chrome Web Store**](https://chromewebstore.google.com/detail/echdjophnbkljbokigbpknajhbjngeic?utm_source=item-share-cb) | [**📂 View on GitHub**](https://github.com/ddx-510/dd-sidebar)

</td>
</tr>
</table>

### 🐟 Moyu (摸鱼) - Master the Art of Looking Busy

<table>
<tr>
<td width="50%" valign="top">

#### 📸 Screenshots

[<img src="https://ddx-510.github.io/moyu-mac/screenshots/aqua-big.png" />](https://ddx-510.github.io/moyu-mac/)

</td>
<td width="50%" valign="top">

**The AI-powered productivity shield for remote workers.**

Take guilt-free breaks while your computer does the "work". Moyu (Chinese for "loafing") is a macOS menu bar application designed to help remote workers and developers take breaks while maintaining the appearance of productivity.

**Features:**
- 🛡️ **Productivity Shield**: Fake Update & Fake Coding screens to deter shoulder surfers
- 💰 **Value Your Time**: Money Counter & Paid Poop Tracker
- 🌊 **The Oasis**: Fish Pond gamification & soothing ocean theme
- 🚨 **Tide Warning**: Notification system for when managers approach

**Tech Stack:** Electron | React | TypeScript | Tailwind CSS

[**📥 Download**](https://ddx-510.github.io/moyu-mac/) | [**📂 View on GitHub**](https://github.com/ddx-510/moyu-mac)

</td>
</tr>
</table>

---

## 🎮 Game Projects

### 🐟 Fish Tank

<table>
<tr>
<td width="50%" valign="top">

#### 📸 Screenshots

[<img src="https://img.itch.zone/aW1hZ2UvNDAwOTA2NS8yMzkwODAzNi5wbmc=/original/26xK7J.png"/>](https://ddx510.itch.io/fish-tank)
[<img src="https://img.itch.zone/aW1hZ2UvNDAwOTA2NS8yMzkwODAzNy5wbmc=/original/qOfXw2.png"/>](https://ddx510.itch.io/fish-tank)

<!-- Add more: [<img src="your-image-url" width="200" />](https://ddx510.itch.io/fish-tank) -->

</td>
<td width="50%" valign="top">

**Interactive Digital Aquarium** - Create, customize, and interact with your own underwater world!

A relaxing, interactive aquarium game where you can design your own fish, watch them swim, and create a beautiful underwater ecosystem. 

**Features:**
- 🎨 **Custom Fish Creation**: Draw unique fish pixel-by-pixel with a built-in drawing tool
- 🏊 **Living Aquarium**: Watch fish swim naturally with realistic physics-based movement
- 🍽️ **Interactive Feeding**: Long-press to drop food and watch fish compete to eat
- 👥 **Social Features**: Vote on fish creations and track popularity
- 🖼️ **Gallery Mode**: Browse through the entire fish collection

**Tech Stack:** Turbo (Rust-based game engine) | Real-time multiplayer | Persistent storage

[**🎮 Play on itch.io**](https://ddx510.itch.io/fish-tank)

</td>
</tr>
</table>

---

### 🃏 Tok Pocket

<table>
<tr>
<td width="50%" valign="top">

#### 📸 Screenshots

[<img src="https://img.itch.zone/aW1hZ2UvMzQ1NTc0OS8yMzM4NTA1MS5wbmc=/original/nmPDJf.png" width="180" />](https://ddx510.itch.io/tok-pocket)
[<img src="https://img.itch.zone/aW1hZ2UvMzQ1NTc0OS8yMzM4NTA0My5wbmc=/original/25AyIM.png" width="180" />](https://ddx510.itch.io/tok-pocket)

</td>
<td width="50%" valign="top">

**Experience intense tactical card combat in this multiplayer strategy game!**

**Game Features:**

⚔️ **Strategic Grid-Based Combat**
- Deploy your cards on a 3x3 battlefield grid
- Plan your attacks and defenses with tactical positioning
- Master the art of card placement timing

🏗️ **Deep Deck Building System**
- Collect cards from multiple factions: Royal, Barbarian, and Undead
- Build and customize your perfect 30-card deck
- Unlock new cards through booster packs

🌐 **Multiplayer Battles**
- Challenge players online in real-time matches

**Tech Stack:** Turbo (Rust-based game engine) | Real-time multiplayer

[**🎮 Play on itch.io <password: turbo>**](https://ddx510.itch.io/tok-pocket) 

</td>
</tr>
</table>

---

## 🛠️ Tools Vibed

### 🔁 D-Decode - Sci-Tech File Converter

<table>
<tr>
<td width="50%" valign="top">

#### 📸 Screenshots
<img width="1302" height="932" alt="image" src="https://github.com/user-attachments/assets/38d5396b-9bda-45ec-810f-0909402ec234" />
</td>
<td width="50%" valign="top">

**Advanced Sci-Tech File Converter**

A versatile online tool for file conversion and data processing.

**Features:**
- 🔄 **Format Conversion**: Convert between various scientific and technical file formats
- 🛠️ **Data Processing**: Simple and efficient data manipulation tools

**Tech Stack:** React | Next.js

[**🔗 Visit Website**](https://d-decode.vercel.app/)

</td>
</tr>
</table>

### 📝 DD-Markup - Markdown Editor

<table>
<tr>
<td width="50%" valign="top">

#### 📸 Screenshots
<img width="1902" height="930" alt="image" src="https://github.com/user-attachments/assets/23f9b692-78d0-4577-a3ca-f2fb6a242ed4" />
</td>
<td width="50%" valign="top">

**Online Markdown Editor**

A clean and simple markdown editor for quick note-taking and formatting.

**Features:**
- ✍️ **Live Preview**: See your markdown rendered in real-time
- 🎨 **Syntax Highlighting**: Clean interface for writing documentation

**Tech Stack:** React | Next.js

[**🔗 Visit Website**](https://dd-markup.vercel.app/)

</td>
</tr>
</table>

### 👁️ Bling Eyes - AI & Social News Feed

<table>
<tr>
<td width="50%" valign="top">

#### 📸 Screenshots
<img width="1885" height="901" alt="image" src="https://github.com/user-attachments/assets/dbb871c9-9ff3-46fc-b966-3eacf1408b60" />

</td>
<td width="50%" valign="top">

**AI & Social News Universe**

A modern news aggregation platform with a sleek interface.

**Features:**
- 📰 **News Aggregation**: Curated news from multiple sources
- 🤖 **AI Integration**: AI-powered summaries and insights (inferred)

**Tech Stack:** React | Next.js | Tailwind CSS

[**🔗 Visit Website**](https://bling-eyes.vercel.app/)

</td>
</tr>
</table>

---

## 📹 Previous Game Demos

### The Tale of Kentridge (Tok - Previous Version)
[![The Tale of Kentridge](https://img.youtube.com/vi/CfYs6wlWDug/0.jpg)](https://www.youtube.com/watch?v=CfYs6wlWDug&t=14s)

**Previous version of Tok Pocket** - Built without Turbo OS but with Solana blockchain integration.

[**Watch on YouTube** →](https://www.youtube.com/watch?v=CfYs6wlWDug&t=14s)

---

### MetalCore
[![MetalCore](https://img.youtube.com/vi/ohToEW5kBoM/0.jpg)](https://www.youtube.com/watch?v=ohToEW5kBoM)

**School Project** - Unreal Engine 3D roguelike game

[**Watch on YouTube** →](https://www.youtube.com/watch?v=ohToEW5kBoM)

---

### AssaShine

**Unreal Engine 3D School Orbital Project** - Top 16 teams

**Topdown party game** with lots of NPCs. Players need to mimic NPCs and find out players (and kill them) with skills.

[**View Demo** →](https://drive.google.com/file/d/1JtRQdXbKe1JXdZph2cF10lFCTyegYR70/view)

---

#### Find out more about me 📫 

- [My personal Blog & some past exp](https://ddx-510.github.io/)

<img src="https://raw.githubusercontent.com/ddx-510/ddx-510/output/snake.svg" alt="Snake animation" />
