# 💖 For My Love – Cinematic Songbook

A premium cinematic digital songbook experience that blends memories, music, and storytelling into a beautiful interactive book.

---
```

## ✨ Features

- 📖 Realistic 3D page-flip book experience  
- 🎵 YouTube-based auto music per page  
- 📱 Fully responsive (mobile + desktop optimized)  
- 💫 Cinematic lighting + glass UI design  
- 🔊 Page flip sound effects  
- 👆 Swipe + keyboard navigation support  
- 🎧 Smooth background music transitions  

---

## 📂 Project Structure
```

```bash

/images
├── 1.jpg
├── 2.jpg
├── ...
└── 25.jpg

index.html
README.md

```

---

## 🎶 How It Works

- Each page is mapped to a specific image (`images/1.jpg`, `images/2.jpg`, etc.)
- Selected pages trigger specific songs via YouTube video ID
- Page flip automatically changes music + UI state
- First page = Cover  
- Last page = Ending Page  

---

## 🚀 Deployment (GitHub Pages)

1. Push project to GitHub repository  
2. Go to **Settings → Pages**  
3. Select:
```

Branch: main
Folder: /root

````
4. Save → Your site goes live instantly

---

## 🎧 Customization

### Add / Change Songs
Edit:
```js
const songMappings = {
2: { title: "Song Name", videoId: "VIDEO_ID", startTime: 30 },
};
````

### Change Pages

* Add images inside `/images`
* Update `TOTAL_PAGES` value

---

## 🧠 Tech Stack

* HTML5
* CSS3 (Tailwind + Custom CSS)
* JavaScript (Vanilla)
* PageFlip.js
* YouTube IFrame API

---

## 🏆 Creator Credit

**Designed & Developed with cinematic detail by:**

> ✨ Built with passion, emotion, and attention to detail
> 💻 Crafted by a developer who turns memories into experiences
> 🎧 Every animation and interaction designed for emotional storytelling

**Creator Signature:**

```
Made with ❤️ by Hamidur Rahman
```

---

## ⚡ HiFi Note

This project is a **high-fidelity interactive experience**, not just a website —
it is designed to feel like a *living memory book* where music, motion, and emotion blend together.

---

## 📜 License

© 2026 – All Rights Reserved
This project is created as a personal cinematic experience and should not be redistributed as a template without permission.

