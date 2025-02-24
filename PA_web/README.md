# Privacy & Architecture Research Website

This repository contains the source code for a website showcasing research on privacy in architecture. The site is designed to display various architectural examples and discuss their implications on privacy.

## Features

- **Consistent Navigation**: A navigation bar is present across all pages, providing easy access to different sections of the site.
- **Image Galleries**: Each page includes a gallery of images with expandable description boxes, offering detailed insights into the research.
- **Responsive Design**: The website is built using Bootstrap, ensuring a responsive layout that adapts to different screen sizes and devices.
- **Templating System**: The site uses a templating system to maintain consistency across pages, with a base layout that is extended by each specific page.

## Structure

- **layout.html**: The base template containing the site's overall structure, including the navigation bar and common elements.
- **home.html, domestic.html, civic.html, transportation.html, about.html, goal.html, method.html, sources.html**: Individual pages extending the base layout, each with its own content and image gallery.

## Technologies Used

- **HTML**: For structuring content.
- **CSS**: For styling, using Bootstrap for responsiveness.
- **JavaScript**: For interactive elements, with jQuery for DOM manipulation.
- **Templating Engine**: Jinja2-style syntax for template inheritance.

## Setup

1. Clone this repository to your local machine.
2. Ensure you have a templating engine or static site generator installed that supports Jinja2-style templates (e.g., Jekyll, Hugo).
3. Replace placeholder images and descriptions with your actual research content.
4. Build the site using your chosen static site generator.

## Contributing

Contributions are welcome! If you have suggestions or improvements for the site, feel free to open an issue or submit a pull request.

## License

This project is licensed under the [MIT License](https://opensource.org/licenses/MIT).

## Acknowledgments

- Special thanks to [Your Name] for the research and content.
- Bootstrap and jQuery libraries used for styling and interactivity.
