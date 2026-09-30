# Nightnoose

A dark, gothic-themed Hangman game that runs in the browser as a single HTML file. Guess a random movie or TV show title letter by letter while its image slowly sharpens with every guess.

## Versions

| File | Content | API | Key needed |
|---|---|---|---|
| `movies.html` | Movies (English) | [TMDB](https://www.themoviedb.org/) | Yes (v3 key or v4 token, entered on first launch, stored in local storage only) |
| `movies-de.html` | Movies (German UI and titles) | [TMDB](https://www.themoviedb.org/) | Yes (same key as `movies.html`, shared via local storage) |
| `tv.html` | TV shows (English) | [TVmaze](https://www.tvmaze.com/api) | No |
| `tv-de.html` | TV shows (German UI) | [TVmaze](https://www.tvmaze.com/api) | No |

## Features

- Random well-known titles (settings at the top of each script: `TOP_PAGES` for movies, `MIN_WEIGHT` for TV shows)
- Image starts heavily blurred and gets a bit sharper with every guess
- 7 wrong guesses allowed, drawn as an SVG gallows
- On-screen and physical keyboard support (Enter starts a new round)
- Vanilla HTML, CSS and JavaScript, no build step

## Run

Open any HTML file in a browser, or host the repo with GitHub Pages.

## Attribution

This product uses the TMDB API but is not endorsed or certified by TMDB. TV data and images from TVmaze (CC BY-SA).
