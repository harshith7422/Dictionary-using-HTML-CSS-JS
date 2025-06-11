# Dictionary App

A simple, web-based dictionary application built with HTML, CSS, and JavaScript, styled to resemble LinkedIn's clean and professional UI. The app allows users to search for word definitions, parts of speech, and example sentences using the free [DictionaryAPI.dev](https://dictionaryapi.dev/).

## Features

- **Search Functionality**: Enter a word to retrieve its definition, part of speech, and example sentence (if available).
- **LinkedIn-Inspired UI**: Clean, professional design with LinkedIn's blue and white color scheme, modern typography, and subtle shadows.
- **Responsive Design**: Adapts to various screen sizes for a consistent experience on desktop and mobile.
- **Error Handling**: Displays user-friendly messages for invalid inputs or words not found.
- **Keyboard Support**: Search by pressing the Enter key.
- **Loading State**: Shows a loading indicator while fetching data.

## Technologies Used

- **HTML**: Structure of the web page.
- **CSS**: Styling with LinkedIn-inspired design, including custom fonts, colors, and shadows.
- **JavaScript**: Handles API requests, DOM manipulation, and event listeners.
- **DictionaryAPI.dev**: Free API for retrieving word data.

## Setup

1. **Clone or Download**:
   - Clone this repository or download the `index.html` file.

2. **Run the App**:
   - Open `index.html` in a web browser (e.g., Chrome, Firefox, Edge).
   - No server or dependencies are required, as the app is a single HTML file with embedded CSS and JavaScript.

3. **Ensure Internet Connection**:
   - The app requires an internet connection to fetch data from the DictionaryAPI.dev API.

## Usage

1. Open the app in a browser.
2. Enter a word in the input field (e.g., "example").
3. Click the "Search" button or press Enter.
4. View the word's definition, part of speech, and example sentence (if provided).
5. If the word is not found or the input is empty, an error message will appear.

## File Structure

```
dictionary-app/
└── index.html  # Main file containing HTML, CSS, and JavaScript
```

## Screenshots

*Main Interface*
![Main Interface](screenshots/main-interface.png)

*Search Result*
![Search Result](screenshots/search-result.png)

*Note*: Screenshots are illustrative; actual rendering may vary by browser.

## Limitations

- Relies on the DictionaryAPI.dev, which may have rate limits or downtime.
- Only supports English words.
- Displays the first definition and example per part of speech for simplicity.
- No offline functionality.

## Future Improvements

- Add support for multiple definitions per part of speech.
- Include pronunciation audio (if supported by the API).
- Implement a history of searched words using local storage.
- Add dark mode toggle for accessibility.

## Contributing

Contributions are welcome! To contribute:

1. Fork the repository.
2. Create a new branch (`git checkout -b feature/your-feature`).
3. Make changes and commit (`git commit -m "Add your feature"`).
4. Push to the branch (`git push origin feature/your-feature`).
5. Open a pull request.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Acknowledgments

- [DictionaryAPI.dev](https://dictionaryapi.dev/) for providing the free API.
- Inspired by LinkedIn's UI design for a professional look and feel.