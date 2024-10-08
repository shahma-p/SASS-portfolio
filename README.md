# Portfolio Website 🌐

This project is a personal portfolio website built using HTML, Sass, and JavaScript. It includes separate HTML files for different sections (Home, About Me, My Projects, Contact) and features a responsive design for an optimal user experience on various devices.

## Features
- **Responsive Design**: The website adapts to various screen sizes, making it accessible on both desktop and mobile devices.
- **Sass Styling**: The website’s styles are organized using Sass, allowing for efficient, modular CSS.
- **Multi-Page Navigation**: Separate HTML pages for each section:
  - `index.html` for the Home page
  - `about.html` for the About Me page
  - `projects.html` for My Projects
  - `contact.html` for the Contact page
- **Smooth Navigation**: The navigation bar allows users to switch between pages effortlessly, with smooth transitions.

## Project Structure
The project includes the following files and folders:
- **index.html**: The main landing page for the portfolio.
- **about.html**: Contains the content for the About Me section.
- **projects.html**: Contains the content for My Projects section.
- **contact.html**: Contains the content for the Contact section.
- **sass/**: Contains all Sass files, including partials for different sections.
  - **main.scss**: The primary Sass file that imports partials and compiles to `main.css`.
  - **_variables.scss**: Holds design variables for easy customization.
  - **_header.scss**, **_footer.scss**, **_about.scss**, etc.: Separate Sass partials for specific sections.
- **css/**: Compiled CSS files.
  - **main.css**: The compiled CSS from `main.scss` for browser compatibility.
- **js/**: JavaScript files to add interactive features, such as smooth scrolling and menu behavior.
- **images/**: A folder for images used throughout the website.
