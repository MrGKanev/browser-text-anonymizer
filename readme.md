# Browser Text Anonymizer

A simple bookmarklet that instantly anonymizes webpage content by replacing text with "Lorem" while preserving numbers as random values. Perfect for taking screenshots while protecting sensitive information.

## Features

- 🔄 Instantly replaces all text with "Lorem" or "Ipsum"
- 🔢 Preserves number, special characters and emoji placement but randomizes them
- 📏 Tries to maintains original text layout and formatting
- 🔒 Works locally in your browser (no data sent anywhere)
- ⚡ One-click operation
- 🖥️ Works on any webpage

## Installation

1. Visit the installation page
2. Drag the "🔒 Anonymize Text" button to your bookmarks bar
3. If dragging doesn't work, right-click the button and select "Add to Bookmarks"

## How to Use

1. Navigate to any webpage you want to anonymize
2. Click the "🔒 Anonymize Text" bookmark in your bookmarks bar
3. Everything will be randomized with "Lorem" text
4. Take your screenshot
5. Refresh the page to restore original content

## Example

Before:

```
Order #1234
Total: $299.99
Customer: John Smith
Status: Shipping
```

After:

```
Lorem #5678
Lorem: $845.32
Lorem: Lorem Lorem
Lorem: Lorem
```

## Privacy & Security

- ✅ Works completely offline
- ✅ No data collection or transmission
- ✅ No external dependencies
- ✅ Open source code

## Technical Details

The bookmarklet uses vanilla JavaScript to:

- Traverse the webpage's DOM tree
- Replace text nodes with "Lorem"
- Preserve but randomize numbers
- Maintain original HTML structure and styling

## Useful Commands

- Continuously watch for changes in the `style.css` file, updating the output file whenever changes occur.

```bash
npx @tailwindcss/cli -i ./assets/style.css -o ./assets/style.min.css --watch
```

- Generate a minified version of the CSS

```bash
npx @tailwindcss/cli -i ./assets/style.css -o ./assets/style.min.css --minify 
```

## License

MIT License - Feel free to use and modify for any purpose.

---

Made with ❤️ for privacy-conscious screenshots
