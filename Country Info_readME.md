
# Country Information by Capital

This is a simple web application that allows users to search for country information by entering the capital city. The application fetches data from the REST Countries API and displays relevant details such as the country name, population, region, languages, and flag.

## How It Works

1. **User Input**: The user enters the name of a capital city in the input field.
2. **Fetch Data**: When the user clicks the "Search" button, the application sends a request to the REST Countries API using Axios.
3. **Display Results**: If a country is found, the application displays the country’s flag, name, population, region, and languages. If no country is found, an error message is shown.

## Files Included

- **index.html**: Contains the structure of the web page, including the HTML and links to external stylesheets and scripts.
- **style.css**: (If present) Custom styles for the web page.
- **app.js**: (If present) Contains the JavaScript code for handling user input and interacting with the REST Countries API.

## Libraries and Resources Used

- **Bootstrap 4.5.2**: Used for styling the form, buttons, and card layout.
- **Font Awesome 6.6.0**: Used for potential icon usage.
- **Google Fonts**: Custom fonts used for styling.
- **Axios**: A promise-based HTTP client used for making requests to the REST Countries API.

## How to Use

1. Open `index.html` in your web browser.
2. Enter the name of a capital city in the input field.
3. Click the "Search" button to retrieve and display information about the corresponding country.

## Example Usage

- If you enter "Paris", the application will display information about France.
- If you enter a non-existent capital or make a typo, an error message will inform you that no country was found.

Enjoy discovering information about countries!

