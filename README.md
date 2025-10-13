# Portfolio Website

A minimal, modern portfolio website with light/dark mode toggle. Built with vanilla HTML, CSS, and JavaScript.

## Features

- Clean, minimal design
- Light and dark mode toggle with localStorage persistence
- Responsive layout for all devices
- Smooth animations and transitions
- SEO-friendly semantic HTML
- Fast loading with no external dependencies

## Live Demo

Visit the live site at: [https://myat555.github.io](https://myat555.github.io)

## Customization

### Update Personal Information

1. **Edit `index.html`**:
   - Update your name, tagline, and bio in the hero section
   - Add your social media links (GitHub, LinkedIn, email)
   - Update project details in the projects section
   - Modify skills in the skills section

2. **Replace Avatar Placeholder**:
   - To use your own profile image, replace the avatar placeholder in `index.html` with:
     ```html
     <img src="your-image.jpg" alt="Your Name" class="avatar">
     ```
   - Add the image file to the repository

### Styling

All styles are in `style.css` with CSS variables for easy customization:
- Colors and theme variables are defined in `:root` and `[data-theme="dark"]`
- Modify spacing, fonts, and colors to match your preferences

## GitHub Pages Setup

This repository is configured to deploy automatically with GitHub Pages:

1. Go to your repository settings
2. Navigate to "Pages" section
3. Under "Source", select the `main` branch
4. Save the settings

Your site will be live at `https://myat555.github.io` within a few minutes.

## Local Development

To run locally:

1. Clone the repository:
   ```bash
   git clone https://github.com/myat555/myat555.github.io.git
   ```

2. Open `index.html` in your browser or use a local server:
   ```bash
   # Using Python
   python -m http.server 8000

   # Using Node.js
   npx http-server
   ```

3. Visit `http://localhost:8000` in your browser

## Technologies Used

- HTML5
- CSS3 (with CSS Variables)
- Vanilla JavaScript
- GitHub Pages

## License

Free to use and modify for your own portfolio.
