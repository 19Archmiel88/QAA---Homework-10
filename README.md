# Country Search App

This web application allows you to search for countries and view detailed information about them. It utilizes the [Restcountries API](https://restcountries.com) to fetch country data.

## Features

- **Search Input:** Enter the name of the country you want to search for.
- **Search Results:** Displayed below the search input, providing information about the matching countries.
- **Detailed Information:** View details such as capital, population, flags, and languages for each country.
- **Responsive Design:** The application is designed to be responsive, providing a seamless experience on various screen sizes.

## Implementation

- The `fetchCountries` function fetches country data from the Restcountries API based on the provided country name.
- The application uses the `Notiflix` library for displaying notifications about search results and errors.
- Results are displayed dynamically based on the number of matching countries:
  - If there is no match, a failure notification is displayed.
  - If there are too many matches, an info notification suggests entering a more specific name.
  - For 2 to 10 matches, individual country cards are displayed.
  - For a single match, detailed information about the country is shown.

## How to Use

1. Open the HTML file in a web browser.
2. Type the name of the country in the search input.
3. View the search results and detailed information about the country.
4. For better visibility on smaller screens, the application adapts its layout.

Feel free to explore and modify the code to suit your needs.
