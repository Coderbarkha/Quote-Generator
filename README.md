Random Quote Generator

This is a simple, beginner-friendly web application that displays a random quote each time the "Get Quote" button is clicked. The quotes are stored in an array within the JavaScript code, and a random quote is selected and displayed in the browser.

 Features

- Displays a random motivational quote on each button click.
- Shows the author of each quote for context.
- Simple, clean, and minimalistic UI.

 Technologies Used

- HTML: Structure of the webpage.
- CSS: Styling of the quote box and text.
- JavaScript: Logic for generating and displaying random quotes.

 Project Structure

├── index.html        Main HTML file containing the structure of the app
├── style.css         Internal CSS styling for the quote box and text
└── script.js         JavaScript for quote generation functionality

 How to Use

1. Clone or Download this repository.
2. Open the `index.html` file in your browser.
3. Click the "Get Quote" button to display a new random quote.

 Code Explanation

- HTML: Sets up a `quote-box` div containing:
  - `quote-text` paragraph for the quote itself.
  - `quote-author` paragraph for displaying the author.
- CSS: Centers and styles the quote box and text for a clean layout.
- JavaScript:
  - An array `quote` stores the quotes and authors.
  - `generateQuote()` function picks a random quote and updates `quote-text` and `quote-author`.

Future Improvements

- Add more quotes to the array for variety.
- Use an external API to fetch quotes dynamically.
- Style the button and text to make the design more interactive.
