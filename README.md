# Movie Finder 🎥

Movie Finder is a sleek and user-friendly application for discovering and searching movies. With trending movie lists, popular recommendations, and a powerful search feature, it’s the perfect tool for casual moviegoers and cinema enthusiasts alike.

## 🌟 Features

- **Discover Trending Movies:** Browse a curated list of trending movies updated regularly.
- **Search for Movies:** Instantly search for movies by title with a responsive and debounced search functionality.
- **Popular Recommendations:** Explore movies sorted by popularity to find what everyone’s talking about.
- **Error Handling & Loading State:** Gracefully handles errors and keeps users informed with a loading spinner.

## 🛠️ Tech Stack

- **Frontend:** React + Vite
- **API:** [The Movie Database (TMDb)](https://www.themoviedb.org/documentation/api)
- **Backend ** Appwrite for tracking user searches and trending movies.
- **Styling:** TailwindCSS 
- **Utilities:** `react-use` for debounced search.

## 🚀 Installation and Setup

1. Clone the repository:
   ```bash
   git clone https://github.com/matei19989/React-semi-fullstack.git
   cd movie-finder
Install dependencies:

bash
Copy
Edit
npm install
Set up your environment variables:

Create a .env file in the project root and add your TMDb API key:
plaintext
Copy
Edit
VITE_TMDB_API_KEY=your_tmdb_api_key
Run the development server:

bash
Copy
Edit
npm run dev
Open the app in your browser at http://localhost:5173.

📦 Features in Action
Search Functionality: Enter a movie title to instantly fetch results.
Trending Section: Displays movies fetched from your backend or an external API.
Fallback Handling: Displays appropriate messages for missing movie titles or API errors.

📸 Screenshots
Home Page

Search Results

Trending Movies

🌐 API Integration
The app fetches movie data from the TMDb API. For details on the API, visit TMDb Documentation.
Backend integration for user analytics is optional and can be configured via Appwrite.

🙌 Contributing
Contributions are welcome! If you have ideas for improvement, feel free to fork the repository and submit a pull request.

🛡️ License
This project is licensed under the MIT License. See the LICENSE file for details.

👏 Acknowledgements
TMDb for the movie data.
React and Vite for powering the application.
Appwrite for backend support (if applicable).
