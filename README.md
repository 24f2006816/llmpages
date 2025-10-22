# Light/Dark Mode Toggle Application

This is a minimal web application demonstrating how to implement a light and dark mode toggle using plain JavaScript and Tailwind CSS. The theme preference is persisted using `localStorage`.

## Features

*   **Theme Toggling:** Switch between light and dark modes with a single button click.
*   **Persistence:** Your theme preference is saved in your browser's local storage, so it persists across sessions.
*   **System Preference:** On first load, if no preference is saved, it respects the user's operating system theme preference.
*   **Fully Responsive:** Built with Tailwind CSS, ensuring a consistent look across various screen sizes.
*   **Single File:** All HTML, CSS (via Tailwind CDN), and JavaScript are contained within a single `index.html` file for simplicity.

## Technologies Used

*   **HTML5:** For the page structure.
*   **Tailwind CSS:** For styling and responsive design.
*   **JavaScript:** For the theme toggle logic and local storage management.

## Getting Started

To run this application, simply open the `index.html` file in your web browser. No complex setup or server is required.

### Local Development

1.  **Clone the repository (if applicable):**
    ```bash
    git clone <repository-url>
    cd <repository-name>
    ```
2.  **Open `index.html`:** Locate the `index.html` file and open it with your preferred web browser.

## Usage

*   Click the "Toggle Dark Mode" (or "Toggle Light Mode") button to switch between the two themes.
*   The text below the button will indicate the current active theme.
*   Reload the page or close and reopen your browser; the application will remember your last chosen theme.

## Project Structure

```
.
├── index.html     # The main application file
├── README.md      # This README file
└── LICENSE        # The MIT License for this project
```

## Contributing

Feel free to fork the repository, make improvements, and submit pull requests. For major changes, please open an issue first to discuss what you would like to change.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
