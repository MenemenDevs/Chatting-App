# 🥔 Mutlu Patatesler Uzun Yaşarlar — A Joyful Chat App

> **"Happy potatoes live long lives."**  
> A lighthearted, potato-themed real-time chat app built with:
> - Firebase (Auth, Realtime DB, Storage)
> - Tailwind CSS (via CDN)
> - Feather Icons
> - Vanilla JavaScript
> - Single HTML file

![Potato Emoji](https://sarkac.org/wp-content/uploads/2022/09/kizarmis-patates.jpg)

---

## 🌟 Features

- 🥔 **Potato-themed UI** with playful animations and emoji rain 🌧️
- 🔐 **Secure authentication** via **Google Sign-In** + optional username/password
- 💬 **Real-time group & private messaging**
- 📸 **Media sharing**: send images, videos, and voice notes
- 🎨 **Fully responsive** — works on mobile & desktop
- 🚀 **Zero build step required** — just deploy the HTML!
- 🧩 **Single-file app** — easy to host anywhere (GitHub Pages, Netlify, Vercel, etc.)

---

## 🛠️ Tech Stack

| Technology        | Purpose                          |
|-------------------|----------------------------------|
| **Firebase**      | Auth, Realtime Database, Storage |
| **Tailwind CSS**  | Styling (via CDN)                |
| **Feather Icons** | Beautiful SVG icons              |
| **Vanilla JS**    | No frameworks — pure simplicity  |
| **HTML5**         | Single-file deployment           |

---

## 🚀 Quick Start (Deploy in 2 Minutes)

### 1. **Create a Firebase Project**
1. Go to [Firebase Console](https://console.firebase.google.com/)
2. Create a new project (e.g., `mutlu-patatesler`)
3. Enable these services:
   - **Authentication** → Google & Email/Password
   - **Realtime Database** → Start in **test mode**
   - **Storage** → Start in **test mode**

### 2. **Get Your Firebase Config**
In your Firebase project settings, copy your config:

```js
const firebaseConfig = {
  apiKey: "YOUR_API_KEY",
  authDomain: "YOUR_PROJECT.firebaseapp.com",
  databaseURL: "https://YOUR_PROJECT-default-rtdb.REGION.firebasedatabase.app",
  projectId: "YOUR_PROJECT",
  storageBucket: "YOUR_PROJECT.firebasestorage.app",
  messagingSenderId: "1234567890",
  appId: "1:1234567890:web:abcdef1234567890"
};