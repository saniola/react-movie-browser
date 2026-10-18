# React Movie Browser

A React single-page application for browsing trending movies and searching The Movie Database (TMDB) catalog, with details, cast, and reviews.

## Features

- Trending movies list on the home page
- Search movies by title with query persisted in the URL
- Movie details page with poster, overview, genres, and rating
- Nested routes for cast and reviews
- Lazy-loaded route components with a loading fallback

## Technology

- React 18 with React Router
- Vite build tooling (SWC-based React plugin)
- Axios for HTTP requests to the TMDB API
- CSS Modules for component styling
- ESLint for linting

## Project structure

```
src/
  api/          TMDB API request functions
  components/   Navigation, movie list, cast, and review components
  pages/        Home, movies search, movie details, and 404 pages
  App.jsx       Route definitions
  main.jsx      Application entry point
```

## Setup

Requires a TMDB API read access token. Create a `.env` file in the project root:

```
VITE_TMBD_API_KEY=your_tmdb_api_read_access_token
```

## Commands

```
npm install      # install dependencies
npm run dev      # start the Vite dev server
npm run build    # build for production
npm run preview  # preview the production build
npm run lint     # run ESLint
```
