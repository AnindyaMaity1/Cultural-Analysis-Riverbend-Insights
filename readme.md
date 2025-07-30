# 🌐 Riverbend Insights – Your Cultural Intelligence Platform

**Riverbend Insights** is a sophisticated web application designed to provide **AI-powered cultural analysis, taste discovery, immersion planning**, and **cross-cultural communication tools**. It seamlessly integrates advanced APIs to deliver powerful insights into cultural trends, user preferences, and global dynamics.

---

## 🎯 Features

- 🎭 **Cultural Analysis**
  Understand and profile individual or collective cultural tastes.
  Generate avatars, charts, and receive AI-powered insights.

- 🔎 **Taste Discovery**
  Explore personalized cultural recommendations (movies, books, music, art, and more).

- 🧳 **Immersion Planning**
  Plan culturally-aligned travel experiences and generate mood boards for your destinations.

- 📊 **Market Intelligence**
  Predict emerging cultural trends and gain insights into niche audiences or regional preferences.

- 🧭 **Cultural Compass**
  Get actionable AI-generated tips for navigating cross-cultural scenarios or etiquette.

- 🗺️ **Cartography**
  Visualize global cultural hotspots and taste landscapes with interactive maps.

- 💬 **LLM Chat**
  Chat in real-time with an intelligent AI model (Gemini) to ask cultural, trend, or taste-based questions.

---

## ⚙️ Technologies Used

| Category   | Technology                                |
|------------|-------------------------------------------|
| **Frontend** | HTML, Tailwind CSS, JavaScript            |
| **Charts** | Chart.js                                  |
| **Maps** | Leaflet.js                                |
| **Markdown** | Marked.js                                 |
| **Auth** | Firebase SDK                              |
| **Fonts** | Google Fonts (Manrope)                    |

---

## 🔌 Integrated APIs

- 🔍 **Qloo API** – Cultural intelligence and taste analysis
- 🖼️ **Clipdrop API** – AI-powered text-to-image generation (Avatars & Moodboards)
- 🧠 **Gemini API** – Large Language Model for chat, insights, and trend predictions

---

## 🚀 Setup & Installation

To run **Riverbend Insights**, you must host the `index2Qloo_api.html` file on a local or cloud server.

### ✅ Prerequisites

- A web server (Apache, Nginx, or Python's HTTP server)
- API keys for:
  - Qloo API
  - Clipdrop API
  - Gemini API
- Firebase project configuration:
  - `apiKey`, `authDomain`, `projectId`, etc.

---

## 🔧 Configuration

Open `index2Qloo_api.html` and find the script block:

```javascript
// Firebase configuration
const firebaseConfig = {
    apiKey: "YOUR_FIREBASE_API_KEY",
    authDomain: "YOUR_AUTH_DOMAIN",
    projectId: "YOUR_PROJECT_ID",
    storageBucket: "YOUR_STORAGE_BUCKET",
    messagingSenderId: "YOUR_MESSAGING_SENDER_ID",
    appId: "YOUR_APP_ID"
};

// API Keys (THESE SHOULD BE SECURED IN A PRODUCTION ENVIRONMENT)
const qlooApiKey = "YOUR_QLOO_API_KEY";
const clipdropApiKey = "YOUR_CLIPDROP_API_KEY";
const geminiApiKey = "YOUR_GEMINI_API_KEY";
