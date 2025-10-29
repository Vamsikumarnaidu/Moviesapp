# 🎬 Movie Search & Favorites App

A simple and elegant web application that allows users to **search movies**, **view details**, and **add favorites**, powered by the [OMDb API](https://www.omdbapi.com/).

## 🚀 Live Demo
> You can host it easily using **GitHub Pages** once pushed.  
> Example URL after deployment:  
> `https://yourusername.github.io/Moviesapp/`

---

## 📖 Features

- 🔍 **Search Movies:** Find movies by title using OMDb API.  
- ⭐ **Favorites List:** Add and remove movies from your favorites (stored in localStorage).  
- 🧾 **Detailed Info:** View full movie details including plot, director, genre, and ratings.  
- 🖼️ **Responsive UI:** Works seamlessly across desktop and mobile devices.  
- ⚡ **Single Page Navigation:** Smooth switching between Search, Favorites, and Detail views.  

---

## 🧰 Tech Stack

- **HTML5** – Structure of the app  
- **CSS3** – Modern, responsive design  
- **JavaScript (ES6)** – Dynamic content, event handling, and API calls  
- **OMDb API** – Fetching movie data

---

## 🧑‍💻 How to Run Locally

1. **Clone the repository**
   ```bash
   git clone https://github.com/Vamsikumarnaidu/Moviesapp.git
Navigate into the project folder

bash
Copy code
cd Moviesapp
Open the project in a live server

If you’re using VS Code, install the Live Server extension.

Right-click on moviesapp.html → Open with Live Server

The app will open at

bash
Copy code
http://localhost:5500/moviesapp.html
Add your OMDb API key

In the <script> section, replace this line with your own key:

js
Copy code
const API_KEY = 'your_omdb_api_key_here';
🖼️ Screenshots
Search Page	Movie Details	Favorites Page

🧠 Folder Structure
csharp
Copy code
Moviesapp/
│
├── moviesapp.html      # Main HTML file
├── README.md           # Project documentation
└── (optionally add) style.css / script.js  # if separated
📡 API Reference
Endpoint:

ruby
Copy code
https://www.omdbapi.com/?apikey=YOUR_API_KEY&s=movie_name
s → Search movies by title

i → Get movie details by IMDb ID

Example:

ruby
Copy code
https://www.omdbapi.com/?apikey=b621611&s=avengers
📈 Future Enhancements
🔐 User authentication for personal lists

🌐 Dark mode toggle

🗂️ Pagination and infinite scroll for search results

📦 Database integration to store user favorites online

👨‍💻 Author
Vamsi Kumar Naidu
📧 Contact Me
🌐 GitHub Profile

📝 License
This project is licensed under the MIT License – feel free to use and modify it.
