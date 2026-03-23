<p align="center">
  <img src="https://img.shields.io/badge/Music-Tuner-1db954?style=for-the-badge&logo=musicbrainz&logoColor=white" alt="Music Tuner Badge"/>
  <img src="https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white" alt="HTML5"/>
  <img src="https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white" alt="CSS3"/>
  <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black" alt="JavaScript"/>
</p>

# 🎵 Music Tuner

> **Feel the rhythm, live the music.**

**Music Tuner** is a sleek, modern web-based music player featuring a curated collection of Tamil & Indian music. Built with pure HTML, CSS, and JavaScript — no frameworks, no dependencies — just clean code and great music.

---

## ✨ Features

| Feature | Description |
|---|---|
| 🏠 **Landing Page** | Stunning hero section with glassmorphism effect and background imagery |
| 🎧 **Home Dashboard** | Browse all 15 tracks with artist-themed cards and one-click playback |
| 🔍 **Smart Search** | Real-time filtering by song name, artist, genre, or custom tags |
| 📂 **Category Browsing** | Filter songs by genre — Tamil Pop, Hip Hop, Classical, Romantic, High Energy, Melody |
| 📚 **Library** | Personal collection view with stats, recently played history, and liked songs |
| 📝 **Playlists** | Pre-built playlists (Tamil Hits, Chill Vibes, Energy Boost, Golden Classics) + create your own |
| ▶️ **Persistent Player** | Fixed bottom player bar with play/pause, next, and previous controls |
| 🎨 **Modern UI** | Dark theme, Spotify-inspired sidebar, SVG icons, smooth animations, and equalizer visualization |

---

## 📸 Pages Overview

### 🖼️ Landing Page (`index.html`)
Full-screen hero with a background image, glassmorphism card, and a "Get Started" CTA that leads to the main app.

### 🏠 Home (`main.html`)
Dashboard with 15 artist cards — each card features a background image of the artist and plays the song on click.

### 🔎 Search (`Home.html`)
Search bar with real-time filtering + category pills to browse by genre. Results display with thumbnails and metadata.

### 📚 Library (`library.html`)
Shows collection stats (total songs, genres, artists), recently played tracks with timestamps, liked songs grid, and a full songs list.

### 🎶 Playlists (`playlist.html`)
Pre-curated playlists with 4-image mosaic covers. Create new playlists via a modal dialog.

---

## 🎵 Song Collection

| # | Song | Artist/Theme | Genre |
|---|---|---|---|
| 1 | Anirudh Hits | Anirudh | Tamil Pop |
| 2 | Andriya Vibes | Andriya | Romantic |
| 3 | Dhanush Boost | Dhanush | High Energy |
| 4 | GV Hits | GV Prakash | Melody |
| 5 | Hip Hop Hits | Various | Hip Hop |
| 6 | Shreya Ghoshal | Shreya Ghoshal | Classical |
| 7 | Shruti Haasan | Shruti Haasan | Romantic |
| 8 | SPB Days | SP Balasubrahmanyam | Classical |
| 9 | STR Mix | Simbu (STR) | Tamil Pop |
| 10 | Vijay Blast | Vijay | High Energy |
| 11 | U1 Drugs | Yuvan Shankar Raja | Melody |
| 12 | Karthik Hits | Karthik | Melody |
| 13 | Antony Blast | Antony | High Energy |
| 14 | Sai Latest Hits | Sai Pallavi | Tamil Pop |
| 15 | AR Hits | AR Rahman | Classical |

---

## 🚀 Getting Started

### Prerequisites
- A modern web browser (Chrome, Firefox, Edge, Safari)
- No installations or build tools required!

### Run Locally

```bash
# Clone the repository
git clone https://github.com/your-username/music-tuner.git

# Navigate to the project
cd music-tuner

# Open in your browser
start index.html        # Windows
open index.html         # macOS
xdg-open index.html     # Linux
```

Or simply **double-click** `index.html` to launch the app.

---

## 📁 Project Structure

```
music-player/
│
├── index.html              # Landing page (entry point)
├── main.html               # Home dashboard with song cards
├── Home.html               # Search & category browsing
├── library.html            # Personal library & stats
├── playlist.html           # Playlists management
│
├── style.css               # Landing page styles
├── style2.css              # Shared layout, sidebar, player & card styles
├── style3.css              # Search page specific styles
├── style-library.css       # Library page specific styles
├── style-playlist.css      # Playlist page specific styles
│
├── img1.jpg                # Hero background image
├── *.webp                  # Artist/song thumbnail images
├── *.mp3                   # Audio tracks
│
└── README.md               # You are here!
```

---

## 🎨 Design Highlights

- **Dark Theme** — Rich `#0f0f0f` background with `#000` sidebar for an immersive experience
- **Spotify-Inspired Sidebar** — Sticky navigation with active state indicators, SVG icons, and an animated equalizer
- **Glassmorphism** — Frosted glass effect on the landing page hero card
- **Google Fonts** — Using [Poppins](https://fonts.google.com/specimen/Poppins) for modern, clean typography
- **Smooth Animations** — Hover transforms, equalizer bounce, and logo pulse effects
- **Green Accent** — Signature `#1db954` green throughout the UI

---

## 🛠️ Tech Stack

| Technology | Usage |
|---|---|
| **HTML5** | Semantic page structure |
| **CSS3** | Styling, animations, glassmorphism, responsive grid |
| **JavaScript** (Vanilla) | Audio playback, search filtering, playlist management |
| **SVG Icons** | Inline SVG for crisp, scalable iconography |
| **Web Audio API** | Native `<audio>` element for music playback |

---

## 🤝 Contributing

Contributions are welcome! Here's how:

1. **Fork** the repository
2. **Create** a feature branch (`git checkout -b feature/amazing-feature`)
3. **Commit** your changes (`git commit -m 'Add amazing feature'`)
4. **Push** to the branch (`git push origin feature/amazing-feature`)
5. **Open** a Pull Request

---

## 📄 License

This project is open source and available under the [MIT License](LICENSE).

---

## 🙏 Acknowledgements

- Song artists and composers featured in the collection
- Design inspired by [Spotify](https://spotify.com)
- [Google Fonts — Poppins](https://fonts.google.com/specimen/Poppins)

---

<p align="center">
  Made with ❤️ and 🎵
</p>
