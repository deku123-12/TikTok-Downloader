# ⚡ We are Legions - TikTok HD Downloader & Custom Renderer

A modern, fast, and feature-rich web application designed to download TikTok videos in true 1080p HD, standard quality, or extract audio (MP3) without watermarks. It also features a built-in client-side custom resolution renderer.

Created by **Lim3rd** • Client-Side Engine

---

## 🌟 Features

- **No Watermark Downloads:** Get clean videos directly from TikTok.
- **True 1080p & HD Support:** Fetch highest-quality streams (`hdplay` and `play` endpoints).
- **Audio Extraction:** Download original audio tracks as MP3.
- **In-Browser Custom Resolution Renderer:** Re-encode and render videos into custom resolutions (1080p Full HD, 720p HD, 480p Data Saver) using the HTML5 Canvas and MediaRecorder API.
- **Multi-Language Support:** Fully localized interface supporting English, Tagalog (Filipino), and Chinese (中文).
- **Sleek Dark UI:** Optimized for both mobile and desktop screens with a modern dark aesthetic.

---

## 🚀 Tech Stack

- **HTML5** & **CSS3** (Responsive layout & modern styling)
- **Vanilla JavaScript (ES6+)** (Async/Await, DOM manipulation, MediaRecorder API)
- **External API:** TikWM API for fast video stream resolution parsing.

---

## 📂 Project Structure

```text
├── index.html      # Main user interface and styling
├── script.js       # App logic, multi-language, API fetching, and canvas renderer
└── README.md       # Project documentation

🌐 How to Use Locally
 * Clone or download this repository.
 * Ensure index.html and script.js are in the same folder.
 * Open index.html using any modern web browser or live server (like VS Code Live Server or Acode).
⚙️ How It Works
 * Paste Link: Input any valid TikTok video link into the text field.
 * Fetch: The app queries the stream data and presents download options (Direct 1080p, Standard HD, MP3).
 * Render (Optional): Use the built-in custom resolution renderer to downscale or re-encode the video stream right inside your browser memory before downloading.
📝 License
This project is open-source and developed for educational and personal utility purposes.
Created by Lim3rd

