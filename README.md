# JokesWebApp

JokesWebApp is a web application built with ASP.NET Core MVC framework. It allows users to view, create, edit, and delete jokes. This README file provides an overview of the project structure and the functionality of each controller action.

## Table of Contents

- Installation
- Usage
- Controllers
- JokesController
- Index
- Details
- Create
- Edit
- Delete
- Contributing
- License

## Installation

To run this project locally, follow these steps:

- Clone the repository: git clone https://github.com/Armin-AF/JokesWebApp.git
- Navigate to the project directory: cd JokesWebApp
- Restore the dependencies: dotnet restore
- Build the project: dotnet build
- Run the application: dotnet run
- Access the web application in your browser at http://localhost:5000

## Usage

Once the application is running, you can perform the following actions:

- View a list of all jokes on the home page.
- Click on a joke to view its details.
- Create a new joke by clicking on the "Create" button.
- Edit an existing joke by clicking on the "Edit" button.
- Delete a joke by clicking on the "Delete" button.

## Controllers

The project includes the following controller:

### JokesController

The JokesController is responsible for handling the CRUD (Create, Read, Update, Delete) operations for jokes.

Index

- URL: /Jokes/Index
- Description: Displays a list of all jokes.
- HTTP Method: GET

Details

- URL: /Jokes/Details/{id}
- Description: Displays the details of a specific joke.
- HTTP Method: GET

Create

- URL: /Jokes/Create
- Description: Displays a form to create a new joke.
- HTTP Method: GET

Create (POST)

- URL: /Jokes/Create
- Description: Creates a new joke based on the form data.
- HTTP Method: POST

Edit

- URL: /Jokes/Edit/{id}
- Description: Displays a form to edit an existing joke.
- HTTP Method: GET

Edit (POST)

- URL: /Jokes/Edit/{id}
- Description: Updates an existing joke based on the form data.
- HTTP Method: POST

Delete

- URL: /Jokes/Delete/{id}
- Description: Displays a confirmation page to delete a joke.
- HTTP Method: GET

DeleteConfirmed

- URL: /Jokes/DeleteConfirmed/{id}
- Description: Deletes a joke based on the provided ID.
- HTTP Method: POST

## Contributing

Contributions to this project are welcome. To contribute, follow these steps:

1. Fork the repository.
2. Create a new branch.
3. Make your changes and commit them.
4. Push your changes to your forked repository.
5. Submit a pull request.

## License

This project is licensed under the MIT License.
