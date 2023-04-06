# NASA API Pictures APP

This is a web application that retrieves and displays pictures of the day from NASA's Astronomy Picture of the Day (APOD) API. The user can add or remove pictures from their favorites list, which is stored in the browser's localStorage.

## Features

- Displays 10 pictures of the day from NASA's APOD API
- Allows the user to add or remove pictures from their favorites list
- Saves the favorites list in the browser's localStorage

## Technologies Used

- HTML
- CSS
- JavaScript

## Installation

1. Clone or download the repository
2. Open `index.html` in your preferred web browser

## Usage

1. Once open, the application will automatically retrieve and display pictures from NASA's APOD API
2. To add a picture to the favorites list, click the "Add to Favorites" button below the picture
3. To remove a picture from the favorites list, click the "Remove Favorite" button below the picture on the favorites 1. page
4. To view the favorites page, click the "Favorites" button in the top right corner of the screen

Note: To use your own API key, replace DEMO_KEY with your API key in the apiKey variable in app.js.

## API Used

[NASA API](https://api.nasa.gov/planetary/apod?api_key=DEMO_KEY)
