# Gemini Clone 🧠🚀

A modern Gemini (AI assistant) clone built with **React.js**. This project features a sleek chat interface, smart AI-driven responses, and a responsive design inspired by Google's Gemini experience.

## Features
- **AI-Powered Chat**: Leverages Google's Generative AI to provide intelligent and context-aware responses.
- **Responsive Design**: Fully optimized for desktop and mobile devices.
- **Customizable Safety Settings**: Includes configurable safety thresholds for content moderation.
- **Dynamic Typing Animation**: Displays responses with a smooth typing effect.
- **State Management**: Uses React Context API for managing global state.

## Tech Stack
- **Frontend**: React.js, CSS
- **AI Integration**: Google Generative AI API
- **State Management**: React Context API

## File Structure

    ```bash
    gemini-clone/
    ├── src/
    |   |── assets/
    │   ├── components/        # Reusable React components
    |   |   |── Main/
    |   |   |   |── Main.css
    |   |   |   └── Main.jsx
    |   |   └── Sidebar/
    |   |       |── Sidebar.css
    |   |       └── Sidebar.jsx
    │   ├── config/            # Configuration files
    │   ├── context/           # React Context API for state management
    │   ├── App.jsx            # Main application component
    │   ├── index.css          # Global styles
    │   └── main.jsx           # Entry point for React
    ├── public/                # Static assets
    ├── package.json          # Project dependencies and scripts
    └── README.md              # Project documentation
    ```

## Installation

1. Clone the repository:
   ```bash
   git clone <PROJECT_URL>
   cd gemini-clone
    ```
2. Install dependencies:
    ```npm install / npm i
    ```

## API setup

- Replace YOUR_GEMINI_API_KEY in src/config/gemini.js with your Google    Generative AI API key.

## Running
    ```bash
    npm run dev
    ```
- open the app in your browser
    ```bash
    http://localhost:5173
    ```

## Configuration

- API Key: Replace YOUR_GEMINI_API_KEY in src/config/gemini.js with your Google Generative AI API key.

- Model Name: Ensure the MODEL_NAME in src/config/gemini.js matches an available model from the Google Generative AI API.

## Troubleshooting

- Error: Must provide a model name: 
Verify that the MODEL_NAME in src/config/gemini.js is correct.

- Error: Invalid safety settings: 
Ensure all safety categories in safetySettings are valid.

- Error: Request is not iterable: 
Check that the input prompt is a valid string.