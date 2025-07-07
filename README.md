# Streamy

A modern movie application built with **React** and styled with **Tailwind CSS**, integrating the **TMDB API** for movie data and **Appwrite** for backend services. This app allows users to browse movies, view detailed information, and track trending movies based on the number of user searches, providing real-time popular movie insights.

## Features

- Browse and search movies using TMDB API
- View detailed movie information (title, release date, popularity, poster, etc.)
- Track trending movies based on user search popularity
- Backend powered by Appwrite
- Responsive design with Tailwind CSS for faster loading and better SEO
- SEO-friendly architecture including optimized metadata, clean URLs, and fast performance to improve search engine ranking

## Tech Stack

- React
- Tailwind CSS
- TMDB API
- Appwrite

## Cloning the Repository

```sh
git clone https://github.com/wwafii/movie-app-react.git
cd movie-app-react
```



## Installation

Install the project dependencies using npm:

```sh
npm install
```


## Set Up Environment Variables

Create a new file named `.env.local` in the root of your project and add the following content:
```sh
VITE_TMDB_API_KEY=

VITE_APPWRITE_PROJECT_ID=
VITE_APPWRITE_DATABASE_ID=
VITE_APPWRITE_COLLECTION_ID=
```


Replace the placeholder values with your actual TheMovieDatabase API and Appwrite credentials.

## Running the Project

Start the development server:
```sh
npm run dev
```

Open [http://localhost:5173](http://localhost:5173) in your browser to view the project.