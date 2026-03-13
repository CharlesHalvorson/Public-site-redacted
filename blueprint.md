# Project Blueprint

## Overview

This project is a personalized website for a user named Jayci. It includes interactive elements to display images and videos, as well as a 3D model viewer.

## Implemented Features

### Initial Setup
- **HTML Structure:** A basic HTML structure with a main heading and a container for buttons.
- **CSS Styling:** Basic styling for the buttons and image containers.
- **JavaScript Interactivity:**
    - **"Press if you are in fact Jayci" Button:** Toggles the display of a grid of singer images and reveals the "green jacket guy" button.
    - **"Press to see what came up when i searched finnish pop singer green jacket" Button:** Toggles the display of a grid of images of a man in a green shirt.
    - **"press if you want some motivation" Button:** Plays a motivational video and audio.
    - **"Click this for a little fun" Button:** Plays a fun video.
    - **"Click here for another video" Button:** Plays another video.
    - **"inside_joke" Button:** Displays a 3D model of the ISS with a zoom slider.
    - **Black Cat Image:** Displays an alert when clicked.

### "Hacky" Button Fix
- **Problem:** The "Hacky" button was not working because it had the same ID as another button.
- **Solution:**
    - Assigned a unique ID to the "Hacky" button (`hacky-button`) and its corresponding image container (`hacky-container`) in `index.html`.
    - Added a new event listener in `main.js` to toggle the visibility of the `hacky-container` when the `hacky-button` is clicked.

## Current Task

### Make the "Hacky" section button work like the others

**Plan:**
1.  **Analyze the code:** Review `index.html` and `main.js` to understand why the "Hacky" button is not working.
2.  **Identify the issue:** The "Hacky" button and its associated image container have duplicate IDs, which is causing a conflict.
3.  **Fix the HTML:** Assign unique IDs to the "Hacky" button and its container.
4.  **Fix the JavaScript:** Add a new event listener to `main.js` to handle the click event for the newly identified "Hacky" button.
5.  **Update the blueprint:** Document the changes in this `blueprint.md` file.
