# Copilot Prize Wheel
An interactive web-based prize wheel game where users can swipe to spin and win various prizes.

## Overview

The Copilot Prize Wheel web app designed for events, conferences, or marketing activations. Users can interact with the application by swiping on the screen to make a character jump and spin the colorful prize wheel. When the wheel stops, the user wins a prize and the character celebrates.

## Prize Configuration

Prizes are configured in the `prizes.js` file as a JSON array of objects, each with:
- `name`: The display name of the prize
- `quantity`: Available inventory (affects probability of winning)
- `path`: Image file path in the images/prizes directory

The system automatically calculates winning probabilities based on the quantity values. You can adjust the quantities to change the odds of winning specific prizes and the probabilities will adjust every 10 spins based on the current state of `prizes.js`.  This allows you to dyanamically change the odds of winning specific prizes without having to restart the app at the booth.

