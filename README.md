# Simple Quote of the Day App 🌟

This is a straightforward web application built using HTML, CSS, and JavaScript. It provides you with a daily inspirational quote along with the author's name.

## How to Use 🤔

1. Open `index.html` in your web browser.
2. You'll see a "Quote of the Day" displayed.
3. Click the "New Quote" button to get a fresh quote.
4. If you want to share the quote, click the "Tweet" button.

## Features 📝

- Provides a new random quote every time you click "New Quote."
- Allows you to share the quote on Twitter with the "Tweet" button.

## Contributing 🛠️

Feel free to fork this repository and customize the code to meet your needs. You can add more features like saving favorite quotes or changing the styling.



## Development Notes 📝

### HTML Structure 🌐

- `index.html`: Contains the basic layout of the quote app, including the quote display area, author information, and buttons.

### Styling 🎨

- `style.css`: Provides basic styling for the quote app.

### JavaScript Logic 🧠

- `main.js`: Contains the logic for fetching random quotes and displaying them.

### Fetching Quotes 📚

- The application fetches random quotes from the [Quotable API](https://quotable.io/).
- The `getQuote` function uses the `fetch` API to retrieve a random quote.
- The quote and author information is updated in the DOM once the data is received.

### Sharing on Twitter 🐦

- The `tweet` function opens a new window with a Twitter intent link, allowing users to share the quote on their Twitter feed.

### Getting Started 🚀

The quote app is ready to use. Open `index.html` in a web browser and start your day with an inspiring quote!

---

Feel free to customize and expand upon this simple quote app to create your own personalized experience! 🌟