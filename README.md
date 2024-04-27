# Local Library

Welcome to the Local Library project!

## Overview

The Local Library project is a simple web application for managing the catalog of a local library. It provides features for librarians to manage the library's collection of books, as well as for patrons to browse and search for books.

## Features

- **Catalog Management**: Librarians can add, edit, and remove books from the library's catalog.
- **Book Availability**: Patrons can check the availability of books in the library's collection.
- **Borrowing and Returning**: Patrons can borrow and return books, with the system automatically updating book availability.
- **Search Functionality**: Users can search for books by title, author, genre, or other criteria.
- **User Authentication**: Librarians and patrons can log in to their accounts to access personalized features.

## Technologies Used

- **Frontend**: HTML, CSS, JavaScript
- **Backend**: Node.js, Express.js
- **Database**: MongoDB (or any other database system you've used)
- **Authentication**: Passport.js (or any other authentication library you've used)

## Installation

To run the Local Library project locally, follow these steps:

1. Clone this repository to your local machine using the following command:

`git clone https://github.com/Ethan-Penaflor/Local-Library.git`


2. Navigate to the project directory:

`cd Local-Library`


3. Install the necessary dependencies:

`npm install`

4. Set up the database:
- Create a MongoDB database for the project.
- Set the database connection URI in the `.env` file.

5. Start the server:

`npm start`


6. Visit `http://localhost:3000` in your web browser to access the Local Library application.

## Usage

Upon accessing the Local Library application, librarians and patrons can perform various actions based on their roles:

- **Librarians**: Log in to manage the library's catalog, including adding new books, editing existing books, and removing books from the collection.
- **Patrons**: Log in to browse the library's catalog, search for books, check book availability, and borrow or return books.

## Contributing

Contributions to the Local Library project are welcome! If you have suggestions for new features, improvements, or bug fixes, please open an issue or submit a pull request.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
