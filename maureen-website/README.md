# Maureen's Personal Website

Welcome to Maureen's personal website project! This project is designed to showcase Maureen's portfolio, skills, and experiences in a clean and modern layout.

## Project Structure

The project is organized as follows:

```
maureen-website
├── src
│   ├── index.html          # Main entry point of the website
│   ├── templates           # Contains HTML templates
│   │   ├── base.html      # Base template for the website
│   │   ├── homepage.html   # Template for the homepage
│   │   └── about.html      # Template for the about page
│   ├── components          # Reusable components
│   │   ├── header.html     # Header component
│   │   ├── nav.html        # Navigation component
│   │   └── footer.html     # Footer component
│   ├── styles              # CSS styles
│   │   └── style.css       # Main stylesheet
│   └── scripts             # JavaScript files
│       └── main.js         # Main JavaScript file
├── package.json            # npm configuration file
├── .gitignore              # Git ignore file
└── README.md               # Project documentation
```

## Setup Instructions

1. **Clone the Repository**: 
   ```bash
   git clone <repository-url>
   cd maureen-website
   ```

2. **Install Dependencies**: 
   Make sure you have Node.js installed. Then run:
   ```bash
   npm install
   ```

3. **Run the Project**: 
   You can use a local server to view the website. For example, you can use `live-server`:
   ```bash
   npx live-server src
   ```

## Usage Guidelines

- The `index.html` file serves as the main entry point and links to the necessary styles and scripts.
- The `templates` directory contains HTML templates that can be extended for different pages.
- The `components` directory holds reusable HTML components like the header, navigation, and footer.
- The `styles` directory contains the CSS styles that define the look and feel of the website.
- The `scripts` directory contains JavaScript files for interactivity.

## Contributing

Feel free to contribute to this project by submitting issues or pull requests. Your feedback and suggestions are welcome!

## License

This project is licensed under the MIT License. See the LICENSE file for more details.