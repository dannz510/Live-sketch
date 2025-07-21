# Live Sketcher Web Application

## Overview
Live Sketcher is an interactive web application that transforms your live camera feed into various artistic sketch styles. Beyond just sketching, it offers a creative "coloring mode" where you can draw, fill areas with color, and add dynamic elements like emojis, images from URLs, and GIFs from Giphy directly onto your live sketch. You can also move, resize, and delete these added elements, providing a fun and versatile platform for digital art and expression.

## Features
* **Live Sketching:** Transforms your webcam feed into different artistic sketch styles in real-time.
* **Multiple Sketch Styles:** Choose from:
    * Classic Sketch
    * Inverted Sketch
    * Pencil Sketch
    * Cartoon/Posterize Effect
    * Sepia Tone
    * High Contrast (Threshold)
* **Mirror Mode:** Toggle mirroring of the camera feed.
* **Coloring Mode:**
    * **Freehand Drawing:** Draw directly on the sketch with a customizable color.
    * **Flood Fill Tool:** Fill enclosed areas with a selected color.
    * **Element Selection & Manipulation:** Select, move, and resize added emojis, images, and GIFs.
    * **Emoji Integration:** Add a variety of pre-defined emojis or paste custom emojis onto your sketch.
    * **Image Embedding:** Embed static images from any URL.
    * **Giphy Integration:** Search for and add static GIFs from Giphy.
* **Undo Last Stroke:** Easily revert your most recent freehand drawing.
* **Delete Selected Element:** Remove any selected emoji, image, or GIF from the canvas.
* **Clear All:** Clear all drawings and added elements from the canvas.
* **Capture & Save:** Save your final masterpiece as a PNG image.

## How to Run

### Option 1: Run Directly from HTML File
1.  Save the entire content of the provided HTML code (including `<!DOCTYPE html>` to `</html>`) into a file named `live_sketch.html`.
2.  Open the `index.html` file using your web browser (e.g., by double-clicking it).

### Option 2: Run via Githack (for GitHub Hosting)
1.  **Create a GitHub Repository:** Go to [GitHub](https://github.com/) and create a new public repository (e.g., `live-sketcher-app`).
2.  **Upload `index.html`:** Upload the `index.html` file (from Option 1) to the root of your GitHub repository's `main` (or `master`) branch.
3.  **Get Raw URL:** Navigate to the `index.html` file in your GitHub repository on the web. Click the "Raw" button and copy the URL from your browser's address bar. It will look like `https://raw.githubusercontent.com/dannz510/Live-sketch/live_sketch.html`.
4.  **Generate Githack URL:** Go to [Githack.com](https://githack.com/). Paste your raw GitHub URL into the input field and click "Hack this URL".
5.  **Access Application:** Use the new Githack URL provided (e.g., `[https://raw.githack.com/YOUR_USERNAME/YOUR_REPO_NAME/main/index.html](https://raw.githubusercontent.com/dannz510/Live-sketch/refs/heads/main/live_sketch.html)`) to access your live application.

## Giphy API Key
The Giphy search feature requires an API key. Please ensure you replace the placeholder `Vpgm2IcVFYvOFj5Q68SNL1uIJcBZ2pMC` with your own valid Giphy API Key. You can obtain a free API key from [Giphy Developers](https://developers.giphy.com/). If the API key is missing or invalid, the Giphy search functionality will not work.

## Technologies Used
* **React:** For building the user interface.
* **Tailwind CSS:** For responsive and utility-first styling.
* **HTML5 Canvas API:** For drawing, image manipulation, and real-time video processing.
* **WebRTC (getUserMedia):** For accessing the user's webcam.
* **Giphy API:** For searching and embedding GIFs.
* **Babel (via CDN):** For on-the-fly JSX transformation in the browser.

## License
This project is open-source and available under the MIT License.
