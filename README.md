# Music Player Component

## Overview

The Music Player Component is a versatile web component designed to enhance the user experience for music playback on your site. It features a fixed footer player that remains visible as users navigate through the application, providing convenient access to playback controls and song information.

## Key Features

- **Fixed Footer Position**: The player stays at the bottom of the viewport, ensuring that music controls are always accessible.
- **Song Information**: Displays the current song’s album art, title, and artist name.
- **Playback Controls**: Includes buttons for playing, pausing, and skipping tracks.
- **Options Menu**: Access additional features or settings.
- **Responsive Design**: Adjusts to various screen sizes with media queries for optimal performance on both desktop and mobile devices.

## Installation

1. **Include the CSS**: Link the provided CSS file in your HTML document’s `<head>` section.

    ```html
    <link rel="stylesheet" href="path/to/your/styles.css">
    ```

2. **HTML Structure**: Use the following HTML structure to integrate the music player into your site:

    ```html
    <!DOCTYPE html>
    <html lang="en">
    <head>
        <meta charset="UTF-8">
        <meta name="viewport" content="width=device-width, initial-scale=1.0">
        <link rel="stylesheet" href="path/to/your/styles.css">
        <title>Music Player</title>
    </head>
    <body>
        <div class="footer-player">
            <div class="footer-player-album">
                <img src="path/to/album-art.jpg" alt="Album Art">
            </div>
            <div class="footer-player-song-name">
                <div class="footer-player-song-indicator">Song Title - Artist</div>
            </div>
            <div class="footer-player-controls">
                <!-- Playback controls go here -->
            </div>
            <div class="footer-player-options">
                <!-- Additional options or settings -->
            </div>
            <div class="footer-player-side">
                <!-- Side icons or features -->
            </div>
        </div>
    </body>
    </html>
    ```

## CSS Details

The CSS for this component is designed to ensure a clean and user-friendly interface:

- **Footer Player**:
  - Height: 75px.
  - Background Color: `rgb(48, 47, 47)`.
  - Layout: Flexbox for alignment and spacing.

- **Player Sections**:
  - **Album Art**: Takes up 30% of the width, with responsive sizing.
  - **Song Name**: Occupies 40% of the width, with a flexible layout.
  - **Controls**: Covers 60% of the width.
  - **Options**: Allocates 15% of the width.
  - **Indicators**: Shows playback status or additional info.

- **Responsive Design**:
  - Media queries for screens narrower than 700px and 1000px to adapt the layout accordingly.

## Contributing

Contributions to enhance or fix issues with this component are welcome. Please submit issues and pull requests to the repository.

