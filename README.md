# Best Beaches in the World

## Overview

This interactive webpage showcases the best beaches in the world. Users can browse through beautiful images, read descriptions, and view the location of each beach on an interactive map.

## Features

- **Dynamic Image Slider**: Beautiful images fetched from Unsplash API based on beach names.
- **Beach Descriptions**: Detailed information about each beach.
- **Interactive Map**: View the location of each beach using Google Maps API.
- **Responsive Design**: Ensures a great user experience on both desktop and mobile devices.

## Technologies Used

- **HTML**: Structure of the webpage.
- **CSS**: Styling and layout.
- **JavaScript**: Dynamic content and interactivity.
- **Unsplash API**: Fetching high-quality images.
- **Google Maps API**: Displaying beach locations on a map.

## Installation

1. Clone the repository:

    ```bash
    git clone https://github.com/Monik2002/best-beaches.git
    ```

2. Navigate to the project directory:

    ```bash
    cd best-beaches
    ```

3. Open `index.html` in your preferred web browser.

## Usage

1. **Browse Beaches**: Scroll through the list of top beaches. Each beach is accompanied by a stunning image and a brief description.
2. **Image Slider**: Use the navigation buttons to cycle through images of different beaches.
3. **View on Map**: Click the "View on Map" button to see the location of the beach on an interactive map.

## API Keys

You will need to replace the placeholder API keys in the `index.html` file with your own keys:

- Unsplash API Key
- Google Maps API Key

To get these keys:

- **Unsplash API**: Sign up at [Unsplash](https://unsplash.com/developers) and create a new application to get your access key.
- **Google Maps API**: Go to the [Google Cloud Console](https://console.cloud.google.com/), enable the Maps JavaScript API, and create credentials to obtain your API key.

## Demo

https://github.com/Monik2002/beaches_JS_Challenge/assets/87751450/6a81455d-a910-4ac0-bb16-27a868681e1a

Replace the placeholders in the `index.html` file:

```html
const accessKey = 'YOUR_UNSPLASH_ACCESS_KEY';

<script async defer 
src="https://maps.googleapis.com/maps/api/js?key=YOUR_GOOGLE_MAPS_API_KEY&callback=initMap"></script>
