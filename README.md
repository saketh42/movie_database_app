# MovieBase

MovieBase is a simple React.js application that allows users to search for movies using the OMDB API. It displays movie posters, titles, years, and types, and supports responsive design for different screen sizes.

## Features

- Search for movies by title.
- Displays movie posters, titles, and other details like year and type.
- Responsive design for mobile and desktop views.
- Fetches movie data from the OMDB API.

## Tech Stack

- **Frontend:** React.js
- **CSS:** Custom styles using CSS (with responsive design)
- **API:** OMDB API

## Setup

### Prerequisites

- Node.js
- npm (Node Package Manager)

### Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/saketh42/movie_database_app.git
   ```

2. Install dependencies:
   ```bash
   cd movie_database_app
   npm install
   ```

3.Run the development server:
```bash
npm start
```

### Deploying
To deploy the app using GitHub Pages:
1. Build the app
   ```bash
   npm rum build
   ```

2. Deploy the app:
```bash
npm run deploy
```

## File structure
```
movie_database_app/
├── public/
│   ├── index.html
│   ├── manifest.json
│   ├── robots.txt
├── src/
│   ├── App.css
│   ├── App.js
│   ├── MovieCard.jsx
│   ├── index.js
│   ├── search.svg
├── package.json
└── README.md
```

- public/index.html: The main HTML file for the app.
- src/App.css: Contains the app's custom styles.
- src/App.js: The main component where the app logic is implemented.
- src/MovieCard.jsx: Component to display individual movie details.
- src/index.js: Entry point for rendering the app.

## API Usage

This app uses the OMDB API to fetch movie data. You can sign up on the `OMDB website` to get your own API key. Replace `710514ca` in the API URL (http://www.omdbapi.com?apikey=710514ca) with your own key if necessary.

## License
This Project is open-source and available under the MIT License
