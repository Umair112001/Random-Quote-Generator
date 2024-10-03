# Random Quote Generator

This simple web application displays random motivational quotes every time the user clicks a button. The quotes are currently hardcoded, but the application can easily be extended to fetch quotes from an external API.

## Features

- Displays a random quote from a predefined list of quotes.
- Includes the author's name for each quote.
- Fetches a new random quote every time the "New Quote" button is clicked.
- Simple and intuitive user interface.

## How It Works

The application consists of the following files:

- **index.html**: The HTML structure of the page.
- **styles.css**: The styling for the application (optional, but can be customized).
- **script.js**: The JavaScript logic for fetching and displaying random quotes.

### How Quotes Are Generated

- The quotes are stored in the `script.js` file array.
- When clicking the "New Quote" button, a random quote is selected from this array using JavaScript's `Math.random()` function.
- The selected quote and its author are then displayed on the page.

## Usage

1. Clone the repository:
   ```bash
   git clone https://github.com/Umair112001/random-quote-generator.git
    
