# 🎧 SoundFlix — Music Streaming Web App

A modern, Spotify-inspired music streaming web application built with **Next.js, React, TypeScript, and Tailwind CSS**. SoundFlix provides a music discovery experience with songs, artists, albums, playlists, and a dedicated music player.

> Discover your sound. Feel every beat. 🎵

## ✨ Features

- 🎵 **Music Discovery** — Explore songs, albums, artists, and playlists.
- 🔍 **Music Search** — Search demo music data by song title, artist, genre, album, or playlist.
- ▶️ **Music Player** — Play available audio previews with a dedicated player interface.
- ❤️ **Liked Songs** — Keep track of your favorite tracks.
- 📂 **Playlist Management** — Browse playlists and create or manage playlists through the app interface.
- 🎤 **Artist & Album Pages** — Explore artist profiles, albums, and their associated tracks.
- 🕘 **Recently Played** — Access recently played music.
- 👤 **Authentication UI** — Login, signup, and profile interfaces.
- ⚙️ **Settings** — Manage available music-player and user preferences.
- 📱 **Responsive Interface** — Designed for desktop and mobile browsing.
- 🎨 **Modern UI** — Clean layouts, reusable components, and Lucide icons.

*Note: This repository currently includes mock music data for the demo experience. It is not a production music-streaming service.*

## 🛠️ Tech Stack

| Technology | Purpose |
|---|---|
| Next.js 16 | React framework and routing |
| React 19 | User interface |
| TypeScript | Type-safe development |
| Tailwind CSS 4 | Styling and responsive layouts |
| Lucide React | Icons |
| Local Storage | Client-side persistence where implemented |
| npm | Package management |

## 📁 Project Structure

```text
SoundFlix/
├── public/
│   └── Static assets
├── src/
│   ├── app/
│   │   ├── album/
│   │   ├── albums/
│   │   ├── artist/
│   │   ├── artists/
│   │   ├── browse/
│   │   ├── liked/
│   │   ├── login/
│   │   ├── playlist/
│   │   ├── playlists/
│   │   ├── profile/
│   │   ├── recently-played/
│   │   ├── search/
│   │   ├── settings/
│   │   ├── signup/
│   │   ├── globals.css
│   │   ├── layout.tsx
│   │   └── page.tsx
│   ├── components/
│   │   ├── layout/
│   │   ├── music/
│   │   ├── player/
│   │   ├── playlist/
│   │   └── ui/
│   ├── context/
│   ├── hooks/
│   ├── lib/
│   └── types/
├── .env.local.example
├── .gitignore
├── next.config.ts
├── package.json
├── package-lock.json
├── postcss.config.mjs
├── README.md
└── tsconfig.json
```

## 🚀 Getting Started

Follow these steps to run SoundFlix locally.

### Prerequisites

- Node.js compatible with Next.js 16
- npm
- Git (optional)

### 1. Clone the Repository

```bash
git clone YOUR_GITHUB_REPOSITORY_URL
```

Replace `YOUR_GITHUB_REPOSITORY_URL` with your actual GitHub repository URL.

### 2. Open the Project Folder

```bash
cd SoundFlix
```

### 3. Install Dependencies

```bash
npm install
```

### 4. Configure Environment Variables

The current demo does not require an API key for its mock music data.

An optional `.env.local.example` file is included for future Jamendo API integration. If you later enable that integration, configure the required environment variable in your local `.env.local` file.

Never commit private API keys or secrets to GitHub.

### 5. Start the Development Server

```bash
npm run dev
```

Open the following URL in your browser:

**http://localhost:3000**

## 📜 Available Scripts

| Command | Description |
|---|---|
| `npm run dev` | Start the development server |
| `npm run build` | Create a production build |
| `npm run start` | Start the production server after building |

## 🖼️ Screenshots

Add screenshots of the actual running application here.

Suggested screenshots:

- Home / Music Discovery
- Browse Music
- Search Results
- Album Details
- Artist Details
- Playlist Page
- Music Player
- Mobile Layout

Save your screenshots inside a folder such as `screenshots/` and reference them using Markdown image links.

Example:

```markdown
![SoundFlix Home](screenshots/home.png)
```

Only add screenshots that you have actually captured from the application.

## 🧭 Application Routes

| Route | Purpose |
|---|---|
| `/` | Home page |
| `/browse` | Browse music |
| `/search` | Search songs and other music content |
| `/albums` | Album collection |
| `/album/[id]` | Album details |
| `/artists` | Artist collection |
| `/artist/[id]` | Artist details |
| `/playlists` | Playlist collection |
| `/playlist/[id]` | Playlist details |
| `/liked` | Liked songs |
| `/recently-played` | Recently played music |
| `/profile` | User profile |
| `/settings` | Application settings |
| `/login` | Login interface |
| `/signup` | Signup interface |

## 🔐 Security

- Do not upload `.env.local` or other files containing secrets.
- Keep credentials and private API keys out of source control.
- Use environment variables for future integrations that require credentials.
- The current demo authentication interfaces should not be treated as production-grade authentication.

## 🚧 Future Improvements

- Integrate a live music search API.
- Improve music recommendations.
- Add secure, persistent user authentication.
- Add backend APIs and database support.
- Synchronize playlists and liked songs across devices.
- Add automated testing and deployment workflows.

## 👨‍💻 Developer

**Debapriyo Chatterjee**

- GitHub: [@debapriyochatterjee](https://github.com/debapriyochatterjee)
- LinkedIn: [debapriyochatterjee](https://www.linkedin.com/in/debapriyochatterjee/)

## ⚖️ Disclaimer

SoundFlix is an independent educational and portfolio project inspired by modern music-streaming interfaces. It is not affiliated with or endorsed by Spotify.

Music samples, artwork, and other demo assets may be provided by third-party sources. Their respective rights remain with their owners.

---

**SoundFlix — Your music, your mood, your world. 🎧**
