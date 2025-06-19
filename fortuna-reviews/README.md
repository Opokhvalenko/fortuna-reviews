# fortuna-reviews# Fortuna - Customer Reviews Section

[DEMO LINK](https://Opokhvalenko.github.io/fortuna-reviews/)

This repository contains the frontend development for an interactive "Customer Reviews" section for the Sales Fortuna website. The section features a responsive review carousel with navigation arrows and pagination, developed using modern web standards and methodologies.

[Link to the mockup](https://www.figma.com/design/i8U9prmitB9HfZ2YuzgYhl/Sales-Fortuna-Technical-task?node-id=0-1&p=f&t=EvIgz7HprhwneOIY-0)

## Features

- **Responsive Design:** Optimized for various screen sizes (desktop, tablet, mobile).
- **Interactive Carousel:** Smooth scrolling of reviews with navigation via arrows.
- **Dynamic Pagination:** Visual indicators for the current card in the carousel.
- **Sass/SCSS:** Utilization of the Sass preprocessor for organized and maintainable styles using variables, mixins, and nesting.
- **Developer-Friendly:** Clean, well-structured HTML and SCSS, easily scalable and maintainable.
- **Full-Width Background Image:** The section features a background image that spans the full width of the screen, while the content remains centered.

## Technologies

- **HTML5:** Content structure.
- **CSS3:** Core styling.
- **Sass (SCSS):** CSS preprocessor for modular and organized style code.
- **JavaScript:** Carousel functionality (scrolling, pagination).

## Installation

To run this project locally, you will need Node.js and npm (or Yarn).

1.  **Clone the repository:**

    ```bash
    git clone (https://github.com/Your_Username/fortuna-reviews.git)
    cd fortuna-reviews
    ```

2.  **Install dependencies:**

    ```bash
    npm install
    # Or, if you are using Yarn:
    # yarn install
    ```

    _Note: This will install Vite, Sass, and other necessary dependencies._

3.  **Start the development server:**
    Start the development server:
    Vite provides a super fast development server with Hot Module Replacement (HMR) for instant updates.

    ```bash

    npm run dev
    ```

Your project will be accessible at http://localhost:5173/ (or another port if 5173 is busy). Any changes you make to HTML, SCSS, or JS files will be automatically reflected in the browser.

## Project Structure (Key Folders)

**index.html:** Main HTML file.
**src/:**Contains all source code.
**src/scss/:**All Sass/SCSS files. main.scss is the entry point.
**src/images/:**All project images (company logos, reviewer photos, icons, background image).
**src/carousel.js:** Main JavaScript file for carousel logic.
**vite.config.js:** Vite configuration file (important for deployment).
**package.json:** Project metadata and scripts.

## Building for Production

To create an optimized production build of the project:

```bash

npm run build
```

This will generate a dist/ folder with minified and optimized assets.

## Deployment to GitHub Pages

This project is configured for easy deployment to GitHub Pages.

# Ensure vite.config.js is configured:

The base property in vite.config.js must be set to your GitHub repository name:

JavaScript

// vite.config.js
import { defineConfig } from 'vite';

export default defineConfig({
base: '/fortuna-reviews/', // <-- MAKE SURE THIS MATCHES YOUR GITHUB REPO NAME!
});

# Deploy using the deploy script:

```bash

npm run deploy
```

This command uses gh-pages to push the contents of the dist/ folder to the gh-pages branch of your GitHub repository.

# Activate GitHub Pages:

After deployment, go to your GitHub repository -> Settings -> Pages. Select the gh-pages branch as your source and click Save. Your site will be live at https://Your_Username.github.io/fortuna-reviews/ (replace Your_Username and fortuna-reviews with your actual details).

## Responsiveness

The carousel and its elements adapt to various screen sizes.

- **Desktop:** Displays 3 cards in a row.
- **Large Desktop:** Displays 2 cards in a row.
- **Medium Tablet:** Displays 1 card in a row.
- **Small Tablet / Mobile:** The carousel becomes vertical, arrows are positioned top/bottom, and cards take full width.

## License

This project is licensed under the MIT License.
