# PetStore Project 🐾

**Project Overview**

This repository contains automated tests for the PetStore application. The project includes both UI and API tests, written in JavaScript using the Playwright framework and organized through the Page Object Model for better code structure and maintainability.

- **UI Tests**: Focused on verifying the functionality of the web application [PetStore](https://petstore.octoperf.com/).
- **API Tests**: Validating endpoints from the [Swagger PetStore API](https://petstore.swagger.io/).

## Technologies Used
Playwright: For writing and running UI and API tests.
JavaScript: Main programming language.
Page Object Model (POM): Organizing test code for better readability and reusability.


## Project Structure


petstore-project/
│
├── tests/                 # Contains all test cases
│   ├── ui/                # UI tests for https://petstore.octoperf.com/
│   └── api/               # API tests for https://petstore.swagger.io/
│
├── pages/                 # Page Object files for UI tests
│
├── utils/                 # Helper functions and utilities
│
└── playwright.config.js   # Playwright configuration file

## Getting Started
**Prerequisites**
Node.js: Ensure that Node.js is installed on your machine.
Playwright: Install Playwright using npm.

**Installation**
Clone the repository:
git clone https://github.com/yourusername/petstore-project.git
Navigate to the project directory:
cd petstore-project
Install the dependencies:
npm install

**Running Tests**
--UI Tests
npx playwright test tests/ui
-- API Tests:
npx playwright test tests/api


## Test Coverage


**UI Tests**
The UI tests cover various functionalities on the PetStore web application, such as:
Navigating through the store
Adding items to the cart
Checking out items
**API Tests**
API tests interact with the PetStore API endpoints and verify:
Pet data management (adding, updating, and deleting pets)
User management (registering, updating, and deleting users)
Order processing


**Contributing**
Contributions are welcome! Feel free to submit a pull request or open an issue.
