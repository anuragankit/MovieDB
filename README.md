# 🎬 MovieDB

A web application to browse, search, and manage popular movies using the TMDB API.

## 🚀 Features

- View popular, trending, and upcoming movies
- Search movies by title
- Add movies to a watchlist
- Infinite scrolling for seamless browsing
- Responsive UI with styled-components
- Tailwind CSS for styling

## 🧪 Technologies Used

- React
- Redux (for state management)
- Redux Thunk (async API calls)
- Axios (HTTP client)
- react-infinite-scroll-component
- Styled-components (or CSS)
- React Router for routing
- Tailwind CSS
- The Movie Database (TMDB) API

## ⚙️ Setup Instructions

1. **Clone the repository**
   ```bash
   git clone https://github.com/anuragankit/MovieDB.git
   cd MovieDB
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
REACT_APP_TMDB_API_KEY=```YOUR API KEY HERE
Start the development server

bash
Copy
Edit
npm start


🔧 Folder Structure
pgsql
Copy
Edit
```MovieDB/
├── public/
├── src/
│   ├── components/
│   ├── pages/
│   ├── redux/
│   │   ├── actions/
│   │   ├── reducers/
│   ├── App.js
│   ├── index.js
├── package.json
├── .env
└── README.md





📜 Available Scripts
npm start – Run the app in development mode

npm run build – Build the app for production


📌 Notes
Make sure you sign up on TMDB and get your API key.

The .env file is ignored by Git, so your API key remains secure.

Tailwind CSS must be properly configured in postcss.config.js and tailwind.config.js.

🧑‍💻 Author
Ankit Anurag



