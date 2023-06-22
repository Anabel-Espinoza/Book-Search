# MERN Stack: Book Search

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)


## Description

This project took a functional Google Books API search engine built with RESTful API and refactored it into a MERN stac k application with GraphQL and Apollo Server. 
The application allows the user to create an account, sign in, search for books, add them to their profile, review previously saved books, and remove books from their list.


## Table of Contents

- [Installation](#installation)
- [Usage](#usage)
- [Credits](#credits)
- [License](#license)


## Installation

To application runs in the browser. 
To run locally: 
- Clone the repository.
- Install required packages. From the terminal: `npm i`
- From the terminal, run the app: `npm run develop`
- Open the browser: `localhost:3000`


## Usage

The link to access the deployed application is: 

The application allows the user to signup/login. The search book option can be accessed without logging in, but the user won't have the option to add a book to their profile.
Once the user has logged in, books can saved by clicking on the "save this book!" button.
All saved books can be found in the "See your Books" section. A book can be removed from this list by clicking the "Delete this Book" button. 

The website looks like the following images:

<img src=./screenshots/MERN-Book-login.png width=70% margin=10px alt="Login"> <img src=./screenshots/MERN-Book-search.png width=70% margin=10px alt="SearchBook"> <img src=./screenshots/MERN-Book-saved.png width=70% margin=10px alt="SavedBooks">

## Credits

- Functional RESTful API given by the GA Tech Bootcamp.

- MERN Module activities used as reference.

- Instructor: Saurav Khatiwada

- Tutor: Vinnie Lopez (assistance to troubleshoot mutation and queries in GraphQL)


## License

This Project is covered by the MIT License.