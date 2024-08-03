# meme-project
## Rickroll Project

This project is a simple webpage that implements the classic "Rickroll" prank. 

### Functionality

* Plays the song "Never Gonna Give You Up" by Rick Astley on autoplay and loop.
* Displays an image of Rick Astley.
* Shows a message "you just got rick rolled :)"

### Code Analysis

The project uses the following technologies:

- **HTML (HyperText Markup Language):** Defines the structure and content of the webpage.
- **CSS (Cascading Style Sheets):** Controls the layout and styling of the webpage (located in a separate file named `style.css`).
- **External Fonts:** Uses the `Libre Baskerville` font from Google Fonts for better typography.

**HTML Breakdown:**

- `<!DOCTYPE html>`: Declares the document type as HTML.
- `<html lang="en">`: Defines the root element of the HTML document and specifies the language as English.
- `<head>`: Contains meta information about the webpage.
  - `<meta charset="UTF-8">`: Defines the character encoding as UTF-8.
  - `<meta name="viewport" content="width=device-width, initial-scale=1.0">`: Makes the webpage responsive by adjusting the width and initial zoom level for different devices.
  - `<title>Document</title>`: Sets the title of the webpage (can be customized).
  - `<link rel="stylesheet" href="style.css"/>`: Links the external CSS stylesheet.
  - `<link rel="preconnect" href="https://fonts.googleapis.com">` and `<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>`: Preconnects to Google Fonts for faster font loading.
  - `<link href="https://fonts.googleapis.com/css2?family=Libre+Baskerville&display=swap" rel="stylesheet">`: Loads the `Libre Baskerville` font from Google Fonts.
- `<body>`: Contains the visible content of the webpage.
  - `<audio autoplay loop>`: Creates an audio element that automatically plays on page load and loops indefinitely.
    - `<source src="Rick-Roll-Sound-Effect.mp3">`: Defines the audio source as an MP3 file named `Rick-Roll-Sound-Effect.mp3` (replace with the actual Rick Astley song).
  - `<div>`: Creates a container element to group related content.
    - `<img src="Rick Astley GIF - Rick Astley Rickastley - Discover & Share GIFs.gif"/>`: Displays an image of Rick Astley (replace with the actual GIF).
    - `<h1>sing with me!</h1>`: Creates a heading element with the text "sing with me!". (Style can be customized in CSS).
    - `<p>you just got rick rolled :)</p>`: Creates a paragraph element with the message "you just got rick rolled :)". (Style can be customized in CSS).
- `</body>` and `</html>`: Close the respective tags.

**Please note:**

* You need to replace the placeholder file names (`Rick-Roll-Sound-Effect.mp3` and `Rick Astley GIF - Rick Astley Rickastley - Discover & Share GIFs.gif`) with your actual audio file and GIF image.
* The CSS file (`style.css`) is not included here but would be used to style the layout and appearance of the webpage elements.

###  Feel free to customize the project further!

You can modify the HTML and CSS to change the text, layout, colors, and other visual aspects of the webpage. 
