# 🎵 Spotify History Wrapped & Analysis Tool

A powerful, client-side dashboard to visualize your **Spotify Listening History**.  
Uncover deep insights, "Nerd Stats", and generate beautiful **Shareable Social Cards** (9:16) for your Instagram Stories or TikTok.

![Preview](preview_image_placeholder.png)

## ✨ Features

- **📊 Comprehensive Dashboard**: View total playtime, top artists, and streams at a glance.
- **📈 Visual Analytics**:
  - **Activity Heatmap**: Github-style contribution graph of your listening habits.
  - **24h Clock**: See what time of day you listen to music most.
  - **Radar Charts**: Weekly listening patterns.
- **🤓 Advanced "Nerd" Stats**:
  - **Gini Coefficient**: Measure how diverse (or repetitive) your music taste is.
  - **H-Index**: The academic metric applied to your artists.
  - **Max Obsession**: The most you've ever played a single song in 24 hours.
- **📱 Social Cards Engine**:
  - Auto-generate **20+ unique story cards** based on your stats.
  - Themes: *Bold, Minimal, Pattern (Dot), Gradient*.
  - Export High-Res (1080x1920) PNGs instantly.
- **🔒 Privacy First**:
  - **100% Client-Side**. Your data *never* leaves your browser. No server uploads.

## 🚀 How to Use

1.  **Open `index.html`** in any modern web browser.
2.  **Drag & Drop** your Spotify JSON file into the upload zone.
3.  Explore your stats!

---

## 📥 How to Get Your Spotify Data
To use this tool, you need your **streaming history** from Spotify. Here is how to get it (it's free!):

### Step 1: Request Data
1.  Go to your [Spotify Account Privacy Settings](https://www.spotify.com/us/account/privacy/).
2.  Scroll down to **"Download your data"**.
3.  Look for **"Extended streaming history"** (recommended for full history) or "Account data" (contains last year).
4.  Click **Request**.
    *   *Note: It can take a few days for Spotify to email you the download link.*

### Step 2: Download & Extract
1.  When you receive the email, download the `.zip` file.
2.  Extract the zip file on your computer.
3.  Look for files named `StreamingHistory_music_0.json`, `StreamingHistory_music_1.json`, etc., or `endsong_0.json` (Extended format).

### Step 3: Analyze
1.  Drag one or multiple of these JSON files into this app.
2.  Enjoy your Wrapped!

---

## 🛠 Tech Stack

*   **Core**: Vanilla JavaScript (ES6+), HTML5, CSS3.
*   **Visuals**: [Chart.js](https://www.chartjs.org/) for graphs.
*   **Export**: [html2canvas](https://html2canvas.hertzen.com/) for generating images.
*   **Fonts**: Montserrat (Google Fonts).

## 📱 Mobile Optimized
Works seamlessly on Desktop, Tablet, and Mobile.
*   *On Mobile*: Layout adapts to single-column flux for easy scrolling.
*   *On Desktop*: Dense grid layout for maximum data visibility.

---
*Disclaimer: This project is not affiliated with Spotify AB.*
