# IITM LLM Code Deployment Project Web App

This repository contains a single-file web application (`index.html`) designed to facilitate the generation and "publication" (via direct download) of various files required for the IITM LLM Code Deployment project. This application serves as a simple, client-side tool to quickly create the necessary project assets.

## Table of Contents

-   [Features](#features)
-   [Files Generated](#files-generated)
-   [How to Use](#how-to-use)
-   [Local Development](#local-development)
-   [Technologies Used](#technologies-used)
-   [License](#license)

## Features

*   **Single-file application:** All HTML, CSS (Tailwind CSS), and JavaScript are contained within `index.html`.
*   **Responsive Design:** Optimized for various screen sizes, from mobile to desktop.
*   **Dynamic File Generation:** Generates file content on the fly, including a unique ID for `uid.txt`.
*   **Direct Download:** Allows users to download each required file directly from the browser.

## Files Generated

The application provides buttons to generate and download the following files:

*   `ashravan.txt`: A simple text file containing a specific name.
*   `dilemma.json`: A JSON file detailing an ethical dilemma.
*   `about.md`: A Markdown file providing information about the project.
*   `pelican.svg`: A Scalable Vector Graphics (SVG) image of a pelican.
*   `restaurant.json`: A JSON file containing example restaurant data.
*   `prediction.json`: A JSON file with sample prediction data.
*   `uid.txt`: A text file containing a dynamically generated unique identifier.
*   `index.html`: The main web application file itself (this file).
*   `LICENSE`: The MIT License text.

## How to Use

1.  **Save the file:** Save the provided `index.html` content into a file named `index.html` on your local machine.
2.  **Open in browser:** Double-click `index.html` or open it with any modern web browser (e.g., Chrome, Firefox, Edge, Safari).
3.  **Generate & Download:** On the web page, you will see a list of files. Click the "Download" button next to each file name to generate and download it to your computer. The `uid.txt` file will generate a new unique ID each time you click its download button.

## Local Development

No specific local development setup is required beyond saving `index.html` and opening it in a browser. All dependencies (Tailwind CSS) are loaded via CDN.

## Technologies Used

*   **HTML5:** For the basic structure of the web page.
*   **Tailwind CSS:** For styling and responsive design (via CDN).
*   **JavaScript (ES6+):** For dynamic content generation and file download functionality.

## License

This project is released under the MIT License. See the `LICENSE` file for the full text.
