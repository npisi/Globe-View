# Globe View

Globe View is a web application that displays a list of countries with their details such as flags, names, capitals, regions, populations, and continents. Users can filter countries by continent, search for a specific country by name, and sort countries by name or population.

## Project Structure

### `index.html`

This is the main HTML file that sets up the structure of the web page. It includes the following sections:
- A navigation bar with a search input, search button, and a dropdown for sorting countries.
- A header with buttons to filter countries by continent.
- A main container to display the list of countries.

### `style.css`

This file contains the CSS styles for the web page. It includes styles for the body, navigation bar, country cards, and responsive design for different screen sizes.

### `script.js`

This file contains the JavaScript code for fetching country data from the REST Countries API, displaying the countries, and implementing the filter, search, and sort functionalities.

## Features

- **Fetch and Display Countries**: Fetches country data from the REST Countries API and displays it in a grid layout.
- **Filter by Continent**: Allows users to filter countries by continent.
- **Search by Country Name**: Allows users to search for a specific country by name.
- **Sort Countries**: Allows users to sort countries by name (A-Z, Z-A) or population (Less to High, High to Less).

## How to Run

1. Clone the repository to your local machine.
2. Open `index.html` in your web browser.

## Dependencies

- [Bootstrap 5.3.0](https://getbootstrap.com/) for styling and responsive design.

## License

This project is licensed under the MIT License.
