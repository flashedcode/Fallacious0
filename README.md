# 🧞‍♂️ PastPaperGenie

**PastPaperGenie** is the ultimate web-based hub for unblocked games and free anime streaming. Built with a highly responsive, custom-animated cyberpunk UI, it allows users to play over 730+ classic and modern browser games instantly—no downloads, no installations, and no blocks.

---
## 📸 Glimpse of the Homepage
![image-alt](/screenshots/homepage.png)

---
## ✨ Features

*   **🎮 Massive Game Library (730+ Titles):** Instantly play popular games directly in the browser. Featured games include:
    *   *Minecraft 1.20.4* (WASM/JS build)
    *   *Five Nights at Freddy's (FNAF)*
    *   *Undertale*
    *   *Kirka.io*
    *   *Friday Night Funkin'*
    *   *Geometry Dash Lite*
*   **📺 Anime Hub:** A dedicated section for streaming anime for free.
*   **📚 Knowledge Base & Articles:** Integrated blog sections for game guides, lore deep-dives, and updates.
*   **🌌 Premium UI/UX:** 
    *   Custom neon color palette with smooth CSS animations (glitch effects, floating orbs, neon pulses).
    *   Custom dynamic cursor with trailing ring effects.
    *   Seamless page transitions using vanilla JavaScript.
*   **📱 Fully Responsive:** Carefully optimized grid layouts that work flawlessly across desktop, tablet, and mobile devices.


---
## 🎮 Game Library (`/select/`)
![image-alt](/screenshots/select.png)
The Game Library is a lightweight, client-side arcade hosting **730+ unblocked browser games** with zero installs, logins, or load delays.

### Highlights
* **730+ Instant Titles:** Plays everything from WebAssembly Minecraft builds (Eaglercraft) and FNAF to classic Flash emulations and indie hits.
* **Instant Filtering:** Zero-latency search bar and 1-click category pills (*Sandbox, Horror, Shooter, RPG, Rhythm, Strategy, Platformer*).
* **Stealth Tools:** Built-in emergency Panic Key (`ESC` redirects instantly to Google Classroom) and tab cloaking (`/cloak.html`).
* **Smart Ingestion Engine:** Combines curated featured titles with an automated dynamic parser that cleans, formats, and deduplicates raw game files on the fly.
---

## 🎬 Anime Streaming Hub (`/anime/`)
![image-alt](/screenshots/anime.png)
The Anime Hub is a custom serverless streaming platform that lets users search, discover, and stream thousands of anime shows directly in the browser.

### Highlights
* **AniList API Integration:** Real-time search and metadata fetching (covers, episode counts, titles) via AniList's GraphQL API.
* **Seamless Embedded Player:** High-performance video playback with dynamically generated episode selection grids supporting up to 1,500+ episodes.
* **Firebase Progress Sync:** Google Auth integration that automatically saves watching progress to Cloud Firestore so users can resume anytime.
* **Futuristic Cyberpunk Theme:** Designed with dynamic floating canvas grids, glowing neon UI elements, and custom smooth cursor tracking.

---
## 📰 Articles & Guides (`/articles/`)
![image-alt](/screenshots/articles.png)
The Articles page is a Guide hub delivering gaming guides, lore breakdowns, and browser gaming insights.

### Highlights
* **Comprehensive Game Guides:** Deep-dives into popular titles like *Minecraft*, *FNAF Lore*, *Friday Night Funkin'*, *ULTRAKILL*, and *Undertale*.
* **Responsive Editorial Layout:** Features a main spotlight card for trending reads alongside a clean 2-column grid system for standard articles.
* **SEO & Monetization Optimized:** Built with targeted SEO copy blocks, ad scripts, and structured metadata for search engine indexing.
* **Interactive Cyberpunk Design:** Styled with animated grid backgrounds, smooth reveal-on-scroll animations, and hover-state visual cues.
  
---

## 🚀 Getting Started

Since PastPaperGenie is a static site, setup is practically instantaneous.
But the massive game library that is over 8 gb will probably be a problem and deployment on github pages with take a long while (30 mins - 1 hour) even for minor changes 
### Prerequisites
You only need a modern web browser. No Node.js, Python, or database setup is required.

### Local Development
1. Clone the repository:
   ```bash
   git clone [https://github.com/flashedcode/pastpapergenie.git](https://github.com/flashedcode/pastpapergenie.git)
