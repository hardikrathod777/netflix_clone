# Netflix Clone with MERN Stack (2024)

## Project Overview

This project is a Netflix Clone built using the **MERN Stack** (MongoDB, Express, React, Node.js). The application allows users to browse trending movies and TV shows, search for content, view detailed information about specific movies/shows, and more.

The clone replicates key features of Netflix's UI and provides a smooth user experience with fast content loading and dynamic data fetched from the TMDB API.

## Features

- **User Authentication**: Register and log in with secure password hashing using JWT and Bcrypt.
- **Browse Content**: Movies and TV shows are fetched from the TMDB API.
- **Search Functionality**: Search for movies, TV shows, or actors.
- **Trending Content**: Dynamic content displayed on the home page based on trending movies/shows.
- **Watch Movies/TV Shows**: Allows users to stream content via embedded links.
- **Protected Routes**: Only logged-in users can access specific routes, e.g., viewing content or search history.
- **Responsive UI**: Fully responsive design optimized for all devices.

## Tech Stack

- **Frontend**: React, Tailwind CSS
- **Backend**: Node.js, Express.js
- **Database**: MongoDB (MongoDB Atlas)
- **Authentication**: JWT (JSON Web Tokens)
- **API**: The Movie Database (TMDB) API
- **State Management**: React Hooks and Context API
- **Other Tools**: Axios, Bcryptjs, Mongoose

## Getting Started

### Prerequisites

Make sure you have the following installed on your system:
- **Node.js** (v16+)
- **npm** or **yarn**
- **MongoDB** (Local or MongoDB Atlas for remote database)
- **TMDB API Key** (Register at [TMDB](https://www.themoviedb.org/))

### Installation

1. **Clone the repository:**
   ```bash
   git clone https://github.com/yourusername/netflix-clone.git
   cd netflix-clone
