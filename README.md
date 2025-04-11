# Meme Generator

This is a simple React project that generates random meme images and lets users add custom top and bottom text. It fetches meme templates from the [Imgflip API](https://api.imgflip.com/get_memes) and updates the image dynamically.

## 📁 Project Structure

- `App.jsx` – Main component that renders the layout.
- `components/Header.jsx` – Contains the header with a logo and title.
- `components/Main.jsx` – Handles the main meme generation logic and form inputs.
- `index.css` – Styling for the whole app.
- `index.html` – Basic HTML setup with a root div.
- `index.jsx` – Entry point for React that renders the `App` component.
- `vite.config.js` – Vite configuration for running the project.
- `package.json` – Project dependencies and scripts.

## 🚀 How to Run

1. **Clone the repo**  
   ```bash
   git clone <your-repo-url>
   cd <project-folder>
   ```

2. **Install dependencies**  
   ```bash
   npm install
   ```

3. **Start the dev server**  
   ```bash
   npm run dev
   ```

4. Open your browser and go to `http://localhost:5173` (or the port Vite displays in your terminal).

## 🛠 Features

- Random meme image generation
- Editable top and bottom meme text
- Clean layout with responsive styling

## 📝 Notes

- The meme image data is fetched from an external API once on component load.