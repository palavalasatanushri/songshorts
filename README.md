# 🎵 SongShorts

A premium, cross-platform music streaming and discovery app built for web and Android.

🌐 **Live Site:** [palavalasatanushri.github.io/songshorts](https://palavalasatanushri.github.io/songshorts/)

---

## ✨ Features

- 🔐 **User Authentication** — Secure sign-up and login via Supabase
- 🎵 **Music Streaming** — Discover and stream short-form tracks
- 📂 **Playlist Management** — Create, manage, and organise custom playlists
- 📴 **Offline Caching** — Listen without internet using local cache
- 📱 **Android App** — Native Android build via Capacitor
- 🚀 **Auto Deployment** — CI/CD pipeline with GitHub Actions → GitHub Pages

---

## 🛠 Tech Stack

| Layer | Technology |
|---|---|
| Frontend | React.js, TypeScript, Vite |
| Styling | Tailwind CSS |
| Backend / DB | Supabase (Auth + PostgreSQL) |
| Mobile | Capacitor (Android) |
| Deployment | GitHub Actions, GitHub Pages |

---

## 🚀 Getting Started

### Prerequisites
- Node.js 18+
- npm

### Install & Run

```bash
# Clone the repo
git clone https://github.com/palavalasatanushri/songshorts.git
cd songshorts/songshorts-frontend

# Install dependencies
npm install

# Start development server
npm run dev
```

### Build for Production

```bash
npm run build
```

---

## 📁 Project Structure

```
songshorts/
├── songshorts-frontend/     # React + Vite web app
│   ├── src/
│   │   ├── components/      # Reusable UI components
│   │   ├── pages/           # App pages (Discover, Library, Profile...)
│   │   ├── context/         # Global state (Player context)
│   │   └── lib/             # Supabase client, offline cache
│   └── android/             # Native Android build (Capacitor)
├── songshorts-backend/      # FastAPI backend
└── .github/workflows/       # GitHub Actions deployment
```

---

## 🔧 Environment Variables

Create a `.env` file in `songshorts-frontend/`:

```env
VITE_SUPABASE_URL=your_supabase_project_url
VITE_SUPABASE_ANON_KEY=your_supabase_anon_key
```

---

## 👩‍💻 Developer

**Palavalasa Tanushri**
📧 tanushri.palavalasa@gmail.com
🌐 [Portfolio](https://palavalasatanushri.github.io/protfolio/)

---

## 📄 License

This project is for personal and academic use.
