# React_Face

# Infinite Scrolling Contact List App

This is an authenticated app that displays a contact list of users with their photos. It utilizes infinite scrolling to load more contacts as the user scrolls down the page.

## Features

- Authentication: The app accepts fake login credentials. Use the following details to log in:
  - Username: too
  - Password: bar

- Post-login Route: After successful login, the user will be redirected to the `/home` route. This route displays the main contact list.

- Logout: The logged-in pages display a logout button. Clicking on this button will redirect the user back to the login page.

- No Server Implementation: The app does not require a server for the fake login functionality.

- Contact List: The contact list displays the user's photo and name. It follows a responsive design and looks correct for at least a 320x480 viewport size.

- Static User List: The app uses a static list of users to display the contact information. You can choose to use either the [randomuser.me API](https://randomuser.me/api/?results=500) or the [randomuser.me documentation](https://randomuser.me/documentation#howto) to fetch random user data.

- Infinite Scrolling: Initially, the app loads a partial list of contacts. As the user scrolls to the end of the page, a loading feedback is displayed, and after a delay of 1 second, more contacts are loaded.

- Open Source Libraries: You are free to use any open-source libraries for this project.

## Getting Started

1. Clone the repository.
2. Install the necessary dependencies by running `npm install`.
3. Start the development server with `npm start`.
4. Access the app in your browser at `http://localhost:3000`.

## Important Note

This project does not include any CSS styling, so the appearance of the contact list may be plain. Additionally, the implementation for changing pages after login may not be working as expected.

Feel free to customize the CSS and fix the page navigation issue as per your requirements.

