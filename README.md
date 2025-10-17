# Perspicacity

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

Beyond Knowledge, Towards Wisdom. Perspicacity is an AI-powered web application for Islamic research, providing users with a tool to ask questions and receive answers sourced from reliable Islamic websites.

## Features

-   **Dual Modes:** Choose between a quick 'Search' for immediate answers or a comprehensive 'Research' mode for in-depth analysis.
-   **Sourced Answers:** All information is sourced from IslamQA.info and IslamWeb.net to ensure reliability.
-   **Conversation History:** The app remembers the context of your conversation for relevant follow-up questions.
-   **Progressive Web App (PWA):** Installable on your device for a native-like experience.

## Getting Started

To run this project locally, you will need to have a local web server. You can use something as simple as Python's built-in server.

1.  **Clone the repository:**
    ```bash
    git clone https://github.com/mdselimdev/Perspicacity.git
    ```
2.  **Navigate to the project directory:**
    ```bash
    cd perspicacity
    ```
3.  **Start a local server:**
    ```bash
    python -m http.server
    ```
4.  Open your browser and go to `http://localhost:8000`.

## Configuration

For the application to function, you need to provide your own API keys.

1.  Open the settings by clicking the gear icon in the top right corner.
2.  Enter your Gemini API Key and Google Cloud API Key.
3.  Click 'Save Settings'.

## Contributing

Contributions are welcome! Please read the [CONTRIBUTING.md](CONTRIBUTING.md) for details on our code of conduct and the process for submitting pull requests.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
