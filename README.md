# Copilot Prize Wheel

An interactive web-based prize wheel game where users can swipe to spin and win various prizes.

## Overview

The Copilot Prize Wheel web app designed for events, conferences, or marketing activations. Users can interact with the application by swiping on the screen to make a character jump and spin the colorful prize wheel. When the wheel stops, the user wins a prize and the character celebrates.

## Prize Configuration

Prizes are configured in the `prizes.js` file as a JSON array of objects, each with:
- `name`: The display name of the prize
- `quantity`: Available inventory (affects probability of winning)
- `path`: Image file path in the images/prizes directory

The system automatically calculates winning probabilities based on the quantity values.

## Technical Details

- Pure JavaScript with no external dependencies (except gifler.min.js for GIF animations)
- HTML5 Canvas for rendering
- Web Audio API for sound effects
- Touch and mouse event support
- Custom font implementation with MonaSans-Bold

## Requirements

- Modern web browser with HTML5 support
- JavaScript enabled
