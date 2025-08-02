# 🎬 MovieDB

A responsive React web application for browsing, searching, and saving popular movies using the TMDB (The Movie Database) API.

---

## 🚀 Features

- 🔥 View Popular, Trending & Upcoming movies
- 🔍 Search movies by title
- 💾 Add movies to your Watchlist
- ⏬ Infinite scrolling for seamless UX
- 📱 Fully responsive and mobile-friendly design
- 🎨 Clean UI with Tailwind CSS & styled-components
- 🎥 Embedded video player for trailers

---

## 🛠️ Tech Stack

- **React**
- **Context API** (Watchlist Management)
- **Axios** (API requests)
- **TMDB API** (Data source)
- **Tailwind CSS**
- **Styled-components**
- **React Router DOM**
- **react-infinite-scroll-component**

---

## ⚙️ Installation and Setup Instructions

### 1️⃣ Clone the Repository

```bash
git clone https://github.com/anuragankit/MovieDB.git
cd MovieDB
```
Install dependencies

bash
Copy
Edit
npm install
Add environment variables
Create a .env file in the root directory and add:

env
Copy
Edit
REACT_APP_TMDB_API_KEY=```YOUR API KEY HERE```
Start the development server

bash
Copy
Edit
npm start


🔧 Folder Structure


```MovieDB/
MovieDB/
├── node_modules/
├── public/
│   └── index.html
├── src/
│   ├── assets/
│   ├── components/
│   │   ├── Banner.css
│   │   ├── Banner.jsx
│   │   ├── MediaPlayer.jsx
│   │   ├── MovieCard.jsx
│   │   ├── MovieDetails.jsx
│   │   ├── Movies.jsx
│   │   ├── Navbar.jsx
│   │   ├── Search.jsx
│   │   ├── SearchResults.jsx
│   │   └── WatchList.jsx
│   ├── context/
│   │   └── WatchlistContext.jsx
│   ├── utils/
│   │   └── api.js
│   ├── App.jsx
│   ├── App.css
│   ├── index.css
│   └── main.jsx
├── .env
├── package.json
├── package-lock.json
└── README.md

```





📜 Available Scripts
npm start – Run the app in development mode

npm run build – Build the app for production


📌 Notes
Make sure you sign up on TMDB and get your API key.

The .env file is ignored by Git, so your API key remains secure.

Tailwind CSS must be properly configured in postcss.config.js and tailwind.config.js.

🧑‍💻 Author
Ankit Anurag



