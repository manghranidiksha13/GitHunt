# GitHunt

GitHunt is a responsive web application that allows users to search for GitHub profiles and view their key statistics and information. It utilizes the GitHub Users API to fetch and display data in a clean, user-friendly interface.

## Features

* **User Search:** Search for any GitHub user by their username.
* **Profile Details:** Instantly view user information including:
    * Profile Picture (Avatar)
    * Name and @username
    * Join Date
    * Bio
    * **Stats:** Number of Repositories, Followers, and Following.
    * **Social & Info:** Location, Website/Blog link, Twitter handle, and Company.
* **Theme Toggle:** Switch between **Dark Mode** and **Light Mode**. The app saves your preference in local storage, so it remembers your choice on your next visit.
* **Responsive Design:** Optimized layout for Mobile, Tablet, and Desktop devices.
* **Error Handling:** Displays a "no search results" message if the username does not exist.

## Technologies Used

* **HTML5:** Semantic structure of the application.
* **CSS3:** Custom styling using CSS Variables (Custom Properties) for easy theming, Flexbox for layout, and Media Queries for responsiveness.
* **JavaScript:** Handles API requests using the `fetch` API, DOM manipulation, and local storage logic for the theme toggle.
* **GitHub API:** Fetches user data via `https://api.github.com/users/`.

## How to Run

1.  **Clone the repository:**
    ```bash
    git clone [https://github.com/manghranidiksha13/githunt.git](https://github.com/manghranidiksha13/githunt.git)
    ```
2.  **Navigate to the project directory:**
    ```bash
    cd githunt
    ```
3.  **Open the application:**
    Simply open the `index.html` file in your preferred web browser.

## Project Structure

* `index.html`: The main HTML file containing the structure of the page.
* `styles.css`: Contains all styling, including light/dark mode color variables.
* `script.js`: Contains the logic for fetching data from the GitHub API, updating the UI, and handling the theme switch.
* `assets/`: Contains images and icons used in the application.

## Default Behavior

Upon loading, the application automatically fetches and displays the profile for `manghranidiksha13` as an example.
