# Programming Jokes App

## Overview
A React application built with Vite that fetches and displays random programming jokes from an API. Demonstrates the use of `useEffect` for side effects, state management with `useState`, and event handling.

## Features
- Fetches a programming joke on app load
- Displays a loading message during API requests
- Button to fetch new jokes on demand
- Clean, responsive UI

## Setup
1. Clone the repository:
   ```bash
   git clone https://github.com/dantekin79-creator/react-side-effects-vite.git
   cd react-side-effects-vite
   ```

2. Install dependencies:
   ```bash
   npm install
   ```

3. Start the development server:
   ```bash
   npm run dev
   ```

4. Open your browser to `http://localhost:5173`

## Usage
- The app will automatically fetch and display a programming joke when it loads.
- Click the "Get a New Joke" button to fetch and display a new joke.
- A "Loading..." message appears while fetching data from the API.

## API
Jokes are fetched from [JokeAPI](https://v2.jokeapi.dev/joke/Programming?type=single)
