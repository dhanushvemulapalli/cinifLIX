# cinifLIX

Project: Movie Search Website

What: This project is a Movie Search website implemented using HTML, CSS, and JavaScript. It utilizes the TMDB (The Movie Database) API to fetch and display movie information based on user queries.

Why: The Movie Search website allows users to search for movies and retrieve details such as the movie title and poster image. It provides a user-friendly interface to explore popular movies and find specific movies of interest.

How: The project is implemented using HTML, CSS, and JavaScript. Here's a breakdown of the main steps:

1. API Configuration:
    - The `APILINK` variable holds the URL for retrieving popular movies.
    - The `IMGPATH` variable holds the base URL for retrieving movie poster images.
    - The `SEARCHAPI` variable holds the URL for searching movies based on user queries.
2. Fetching and Displaying Movies:
    - The `returnMov` function is called with the `APILINK` URL to fetch popular movies.
    - The function uses the `fetch` API to retrieve data from the TMDB API.
    - The fetched data is converted to JSON format and processed.
    - For each movie, a `div` element with the class `card` is created.
    - Inside the card, an `img` element is created to display the movie poster.
    - A `h3` element is created to display the movie title.
    - The elements are appended to the appropriate parent elements.
    - The parent elements are appended to the `main` element in the HTML.
3. User Search Functionality:
    - The `form` element and `search` input element are selected.
    - An event listener is added to the form's `submit` event.
    - When the form is submitted, the event listener function is triggered.
    - The function prevents the default form submission behavior.
    - The `main` element's HTML is cleared.
    - The value of the `search` input is retrieved.
    - If a search query is entered, the `returnMov` function is called with the search URL.
    - The search input is cleared after the search is performed.

The project requires integration with HTML and CSS to provide the necessary structure and styling for the website. Additionally, it requires an API key from TMDB to access the movie data.

This project demonstrates proficiency in HTML, CSS, and JavaScript, as well as API integration and data manipulation. It showcases skills in fetching data, dynamically creating HTML elements, and handling user input.
