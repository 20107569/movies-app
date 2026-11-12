# Movies App

A React web app for discovering movies, exploring cast and crew details, and saving favourites. The frontend gets movie data from The Movie Database (TMDB) through a custom Movies API.

## Features

- Browse popular, top-rated, upcoming and now-playing movies.
- Browse movies by genre.
- View movie details, images, reviews, cast and crew, recommendations, and where to watch.
- View a person's details and the movies they worked on.
- Create an account and log in. The site header updates when a user logs in.
- See validation messages when a username or password is invalid.
- Add and remove movies using the favourite button.

## Backend APIs

- **Movies API** fetches movie lists, genres, movie details and person information from TMDB for the React frontend.
- **Users API** handles sign-up and login. The React app uses an authentication context to track login state.
- **Favourites API** uses a Mongoose model to store favourites. It supports `GET` to retrieve favourites, `POST` to add a favourite and `DELETE` to remove one. The favourite button connects to this API.

## Technologies Used

- **Frontend** — React
- **Backend** — Node.js and Express
- **Database** — MongoDB and Mongoose
- **Movie data** — [The Movie Database (TMDB)](https://www.themoviedb.org/)
