# Movie Search Application

A modern React-based movie search application that allows users to discover and search for movies using the TMDB API. The application features a clean, responsive design with real-time search functionality and trending movies section.

## Live Demo

Check out the live application: [Moviskape](https://moviskape.netlify.app/)

## Features

- 🔍 Real-time movie search with debouncing
- 🎬 Trending movies section
- 🎨 Modern UI with Tailwind CSS
- ⚡ Fast and responsive design
- 🔄 Integration with TMDB API
- 📊 Search analytics tracking

## Tech Stack

- React 19
- Vite
- Tailwind CSS
- Appwrite (for backend services)
- TMDB API

## Prerequisites

- Node.js (Latest LTS version recommended)
- TMDB API key

## Getting Started

1. Clone the repository:
```bash
git clone <repository-url>
cd my-first-react-app
```

2. Install dependencies:
```bash
npm install
```

3. Create a `.env` file in the root directory and add your TMDB API key:
```
VITE_TMDB_API_KEY=your_api_key_here
```

4. Start the development server:
```bash
npm run dev
```

The application will be available at `http://localhost:5173`

## Available Scripts

- `npm run dev` - Start development server
- `npm run build` - Build for production
- `npm run preview` - Preview production build
- `npm run lint` - Run ESLint

## Project Structure

```
src/
├── assets/         # Static assets
├── components/     # React components
├── App.jsx        # Main application component
├── main.jsx       # Application entry point
├── appwrite.js    # Appwrite configuration
└── index.css      # Global styles
```
