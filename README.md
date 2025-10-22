# GitHub Pages Project Hub

This repository hosts a simple collection of files published as a public GitHub Pages site. The `index.html` serves as a central hub, providing direct links to all the other hosted files.

## Table of Contents

- [Project Description](#project-description)
- [Files Overview](#files-overview)
- [Setup and Deployment](#setup-and-deployment)
- [License](#license)

## Project Description

This project demonstrates how to set up a basic GitHub Pages site to serve various types of content, from plain text and markdown to JSON and SVG images. The `index.html` file, styled with Tailwind CSS, acts as a navigational interface to explore these different assets.

## Files Overview

Below are the files included in this project, along with their intended content:

*   **`index.html`**: The main entry point for the site. It's a single-file HTML application, fully responsive, providing links to all other files.

*   **`ashravan.txt`**: A 300-word short story by Brandon Sanderson.
    ```
    The wind, a bitter sculptor of the Peaks of Ashravan, howled its ancient song. Elara pulled her cloak tighter, the frostbite nips already testing her resolve. Below, the Vale of Whispers lay shrouded in perpetual twilight, a place where legends claimed the very air remembered the prayers of forgotten gods. Her journey to the Sunken Temple was desperate. The village elders had spoken of the 'Heart of the Vale,' a crystalline shard rumored to mend the severing. Young Kael, her brother, had been afflicted by the Shadowblight, its tendrils slowly drawing the light from his eyes. They said only the Heart, bathed in the dawn's first light from the highest spire, could reverse the curse. With each step, the treacherous ice groaned, and phantom whispers seemed to caress her ears, tempting her to turn back. But Kael's fading smile was a fire in her soul, pushing her onward, against the relentless gales and the growing dread. The peak loomed, a jagged tooth against the bruising sky, promising either salvation or eternal slumber in its icy grasp.
    ```

*   **`dilemma.json`**: An AI moral choice JSON object.
    ```json
    {
      "scenario": "A self-driving car is approaching a narrow bridge. Ahead, a large truck has lost control and swerved into the path, making collision unavoidable. Two options are presented:",
      "option_A": {
        "action": "Swerve left, hitting a pedestrian who is an elderly, critically ill patient on a life support machine.",
        "outcome": "The car's occupants (two healthy young adults) survive. The pedestrian dies. Minimal property damage to the car."
      },
      "option_B": {
        "action": "Continue straight, colliding with the truck.",
        "outcome": "The car's occupants (two healthy young adults) die. The pedestrian is unharmed. Significant property damage to both vehicles."
      },
      "question": "Which action should the AI prioritize, given a utilitarian framework?"
    }
    ```

*   **`about.md`**: A brief self-description in three words.
    ```
    Curious, Creative, Code-driven.
    ```

*   **`pelican.svg`**: An SVG image of a pelican on a bicycle.
    ```xml
    <svg width="200" height="200" viewBox="0 0 200 200" xmlns="http://www.w3.org/2000/svg">
      <!-- Ground -->
      <line x1="0" y1="150" x2="200" y2="150" stroke="#333" stroke-width="2" />

      <!-- Bicycle Frame -->
      <circle cx="60" cy="150" r="20" fill="none" stroke="#666" stroke-width="3" />
      <circle cx="140" cy="150" r="20" fill="none" stroke="#666" stroke-width="3" />
      <line x1="60" y1="150" x2="140" y2="150" stroke="#666" stroke-width="3" />
      <line x1="60" y1="150" x2="100" y2="100" stroke="#666" stroke-width="3" />
      <line x1="140" y1="150" x2="100" y2="100" stroke="#666" stroke-width="3" />
      <line x1="100" y1="100" x2="100" y2="70" stroke="#666" stroke-width="3" />
      <line x1="60" y1="150" x2="60" y2="130" stroke="#666" stroke-width="2" />
      <line x1="140" y1="150" x2="140" y2="130" stroke="#666" stroke-width="2" />

      <!-- Pelican Body -->
      <ellipse cx="100" cy="90" rx="35" ry="25" fill="#ADD8E6" stroke="#000" stroke-width="2" />

      <!-- Pelican Head -->
      <circle cx="125" cy="70" r="15" fill="#ADD8E6" stroke="#000" stroke-width="2" />
      <circle cx="120" cy="67" r="3" fill="#000" />

      <!-- Pelican Beak -->
      <path d="M135,75 Q155,70 160,85 L150,90 Q140,80 135,75 Z" fill="orange" stroke="#000" stroke-width="2" />

      <!-- Pelican Wing -->
      <path d="M100,90 Q110,65 130,80 Q120,100 100,90 Z" fill="#87CEEB" stroke="#000" stroke-width="1.5" />
    </svg>
    ```

*   **`restaurant.json`**: A recommendation for a restaurant in Bangalore, including coordinates.
    ```json
    {
      "name": "Toit Brewpub",
      "cuisine": "Pub Food, Craft Beer",
      "location": "Indiranagar, Bangalore",
      "address": "100 Feet Road, Indiranagar, Bengaluru, Karnataka 560038",
      "coordinates": {
        "latitude": 12.9784,
        "longitude": 77.6408
      },
      "rating": 4.5,
      "description": "A popular microbrewery in Bangalore known for its excellent craft beers, lively ambiance, and delicious pub grub. A must-visit for beer enthusiasts."
    }
    ```

*   **`prediction.json`**: A hypothetical prediction for the Fed rate by December 2025.
    ```json
    {
      "entity": "Federal Reserve",
      "metric": "Federal Funds Rate (Upper Bound)",
      "date": "December 31, 2025",
      "prediction": "4.25%",
      "confidence_level": "Medium",
      "rationale": "Anticipated gradual easing of monetary policy following sustained decline in inflation towards target levels, coupled with moderating but stable economic growth."
    }
    ```

*   **`LICENSE`**: The full text of the MIT License, which governs this project.

*   **`uid.txt`**: This file is expected to be present in the project root as-is, as per the additional context provided by the user.

## Setup and Deployment

To set up and deploy this project as a public GitHub Pages site:

1.  **Create a New Repository**: Initialize a new GitHub repository.
2.  **Add Files**: Create the `index.html`, `README.md`, and `LICENSE` files in the root of your repository with the content provided.
3.  **Create Other Files**: Manually create the following files in the repository root and populate them with the content provided in the 'Files Overview' section above:
    *   `ashravan.txt`
    *   `dilemma.json`
    *   `about.md`
    *   `pelican.svg`
    *   `restaurant.json`
    *   `prediction.json`
    *   Ensure `uid.txt` (from your provided attachment) is also in the root.
4.  **Commit and Push**: Commit all these files to your `main` (or `master`) branch and push them to your GitHub repository.
5.  **Enable GitHub Pages**: Go to your repository settings on GitHub, navigate to 'Pages', and configure GitHub Pages to deploy from the `main` (or `master`) branch's `/ (root)` directory.
6.  **Access Site**: Your site will be live at `https://<your-username>.github.io/<your-repository-name>/` (e.g., `https://ashravan.github.io/my-project-hub/`). It may take a few minutes for the deployment to complete.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
