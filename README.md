# CineSeek Movie Web
CineSeek is a modern movie discovery application built with Next.js, TypeScript, and Tailwind CSS. The application allows users to browse movies from the MoviesDatabase API, view movie details, and search for films by year or genre. The project focuses on creating a responsive, well-structured web application with proper API integration and TypeScript typing.

# Requirements
## Technical Stack
- Next.js 14 (Pages Router)
- TypeScript
- Tailwind CSS
- Font Awesome icons
- MoviesDatabase API - [MoviesDatabase](https://rapidapi.com/SAdrian/api/moviesdatabase)

## Development Requirements
- Node.js (v16 or higher)
- npm or yarn
- Git for version control

# File Structure
```
alx-movie-app/
├── components/
│   ├── commons/
│   │   ├── Button.tsx
│   │   ├── Loading.tsx
│   │   └── MovieCard.tsx
│   └── layouts/
│       ├── Footer.tsx
│       ├── Header.tsx
│       └── Layout.tsx
├── interfaces/
│   └── index.ts
├── pages/
│   ├── api/
│   │   └── fetch-movies.ts
│   ├── movies/
│   │   └── index.tsx
│   ├── _app.tsx
│   └── index.tsx
├── public/
├── styles/
│   └── globals.css
├── .env.local
├── .eslintrc.json
├── .gitignore
├── next.config.js
├── package.json
└── tsconfig.json

```


## API Integration
The application uses the MoviesDatabase API with the following key endpoints: - /titles - Main endpoint for fetching movie data - Supports filtering by year and genre - Implements pagination for browsing through results

## Authentication
- API key authentication via headers
- Environment variable storage for API key
- Server-side API route to protect client-side exposure of keys

# API Overview
Collection of information for movies, tv-shows, actors. Includes youtube trailer url, awards, full biography, and many other usefull informations. This api provides complete and updated data for over 9 million titles ( movies, series and episodes) and 11 million actors / crew and cast members.

<p>Author <i>George Okumu</i></p>

