# Notepad Website

## Overview

This project is a simple **Notepad Website** created using **HTML**, **CSS**, and **JavaScript**. The site provides basic text editing features, allowing users to write, edit, and save notes directly in the browser. It was created to showcase front-end development skills as part of my Hacktoberfest contributions.

## Features

- **Text Editing**: Write and edit plain text in the notepad.
- **Save Notes**: Save your notes locally using the browser’s `localStorage`, so your notes persist even after you close the browser.
- **Clear Notes**: Easily clear the current note to start fresh.
- **Responsive Design**: The design is responsive, ensuring a seamless experience across different devices.

## Demo

You can access the live version of the website [here](#). *(Add link to live project if hosted)*

## Screenshots

![Screenshot of Notepad Website](path-to-screenshot-image)

## Technologies Used

- **HTML**: Structuring the webpage.
- **CSS**: Styling and layout of the page.
- **JavaScript**: Dynamic functionality for saving, loading, and clearing notes.

## Code Snippets

### HTML

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Notepad</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <div class="container">
        <h1>Notepad</h1>
        <textarea id="notepad" placeholder="Start writing..."></textarea>
        <div class="buttons">
            <button onclick="saveNote()">Save Note</button>
            <button onclick="clearNote()">Clear Note</button>
        </div>
    </div>
    <script src="script.js"></script>
</body>
</html>
