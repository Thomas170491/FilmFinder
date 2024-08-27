# Movie Recommendation App

This is a simple Movie Recommendation App that fetches data from The Movie Database (TMDb) API to display random movie suggestions based on selected genres.

## Table of Contents

- [Introduction](#introduction)
- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [API Key Setup](#api-key-setup)
- [Project Structure](#project-structure)
- [Technologies Used](#technologies-used)
- [License](#license)

## Introduction

The Movie Recommendation App allows users to get a random movie recommendation based on a genre they select. The app utilizes TMDb API to fetch genres and movies, and then displays information about a randomly selected movie.

## Features

- Fetch and display a list of movie genres.
- Select a genre and get a random movie suggestion.
- Display detailed information about the selected movie, including title, overview, and poster.

## Installation

To run this project locally, follow these steps:

1. Clone this repository:
    ```bash
    git clone https://github.com/your-username/movie-recommendation-app.git
    ```
2. Navigate to the project directory:
    ```bash
    cd movie-recommendation-app
    ```
3. Open `index.html` in your preferred web browser.

## Usage

1. Upon opening the app, the genre dropdown will populate automatically with options fetched from TMDb.
2. Select a genre from the dropdown menu.
3. Click the "Play" button to get a random movie suggestion based on the selected genre.
4. The app will display the movie's details, including the title, overview, and poster image.

## API Key Setup

To use this app, you need an API key from [The Movie Database (TMDb)](https://www.themoviedb.org/).

1. Sign up or log in to your TMDb account.
2. Go to your account settings and navigate to the API section.
3. Request an API key.
4. Replace the placeholder `YOUR_API_KEY_HERE` in the `script.js` file with your actual TMDb API key:
    ```javascript
    const tmdbKey = "YOUR_API_KEY_HERE";
    ```

## Project Structure


- `index.html`: The main HTML file that contains the structure of the web page.
- `style.css`: The CSS file that contains the styling for the web page.
- `index.js`: The JavaScript file that contains the logic for fetching data from the TMDb API and displaying the movie information.

## Technologies Used

- HTML5
- CSS3
- JavaScript (ES6+)
- [TMDb API](https://www.themoviedb.org/documentation/api)


