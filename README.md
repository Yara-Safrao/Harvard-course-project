# Google Search Frontend

This project is a simple front-end implementation of Google Search, Google Image Search, and Google Advanced Search using HTML and CSS. The website allows users to perform searches and is styled to resemble Google's interface.

## Features

### 1. Google Search
- A homepage with a centered search bar and buttons for "Google Search" and "I'm Feeling Lucky".
- Links to navigate to the **Image Search** and **Advanced Search** pages.
- The search bar has rounded corners, and the layout is styled to match Google's aesthetic.

### 2. Google Image Search
- A dedicated page for performing Google Image searches.
- A hidden input field ensures that the search queries are sent with the appropriate parameter (`tbm=isch`) for image searches.
- Includes navigation links to return to the **Google Search** page or go to the **Advanced Search** page.

### 3. Google Advanced Search
- A page for advanced search options with four fields:
  - **All these words**: Searches for all the specified words.
  - **This exact phrase**: Searches for the exact phrase provided.
  - **Any of these words**: Searches for any of the specified words.
  - **None of these words**: Excludes pages containing these words.
- An "Advanced Search" button styled with a blue background and white text.
- Includes navigation links to return to the **Google Search** page or go to the **Image Search** page.

## File Structure

```
.
├── index.html         # Google Search homepage
├── images.html        # Google Image Search page
├── advanced.html      # Google Advanced Search page
├── styles.css         # CSS for styling the pages
└── README.md          # Project documentation
```

## Installation

1. Clone this repository:
   ```bash
   git clone https://github.com/your-username/google-search-frontend.git
   ```
2. Navigate to the project directory:
   ```bash
   cd google-search-frontend
   ```
3. Open any of the `.html` files in your browser to view the respective pages.

## Usage

1. Open `index.html` in your web browser.
2. Use the search bar to perform a Google search or click "I'm Feeling Lucky" to go directly to the first result.
3. Navigate to the **Image Search** or **Advanced Search** pages using the links in the top-right corner.
4. Perform image searches or advanced searches as needed.



## Technologies Used

- **HTML**: For creating the structure of the web pages.
- **CSS**: For styling the pages to match Google's aesthetic.

## Contributing

Contributions are welcome! If you'd like to contribute to this project, please fork the repository and submit a pull request.

1. Fork the repository.
2. Create a new branch:
   ```bash
   git checkout -b feature-name
   ```
3. Commit your changes:
   ```bash
   git commit -m "Description of changes"
   ```
4. Push to the branch:
   ```bash
   git push origin feature-name
   ```
5. Open a pull request.

## License

This project is licensed under the MIT License. See the `LICENSE` file for details.
