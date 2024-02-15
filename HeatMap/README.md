# HatMap Project

This project visualizes Google Takeout location data using Google Maps API and heatmap.

## Usage
1. Clone the repository.
2. Obtain a Google Maps API key and replace `YOUR_GOOGLE_MAPS_API_KEY` in `public/index.html`.
3. Run the server using `node server.js`.
4. Open `http://localhost:3000` in your browser.

## Project Structure
- `public/`: Frontend files.
  - `css/`: Stylesheets.
    - `style.css`: Custom styles.
  - `js/`: JavaScript files.
    - `app.js`: Google Maps visualization logic.
  - `index.html`: Main HTML file.

- `data/`: JSON file containing location history.

- `server.js`: Node.js server to serve static files.

## License
This project is licensed under the MIT License.
