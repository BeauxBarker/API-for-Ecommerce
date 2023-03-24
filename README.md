# Express.JS API

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

API built using express.js for React eCommerce website.

## Table of Contents

- [Installation](#installation)
- [Usage](#usage)
- [API Documentation](#api-documentation)
- [Tests](#tests)
- [License](#license)

## Installation

1. Clone the repository: `git clone https://github.com/BeauxBarker/API-for-Ecommerce.git`
2. Navigate to the project directory: `cd {repository}`
3. Install the dependencies: `npm install`

## Usage

To start the server, run `npm start`. By default, the server will listen on port 3000. You can change this by setting the `PORT` environment variable.

| Route               | Method | Description                                                                                         |
|---------------------|--------|-----------------------------------------------------------------------------------------------------|
| `/auth/register`    | `POST` | Register a new user                                                                                 |
| `/auth/login`       | `POST` | Login an existing user                                                                              |
| `/auth/logout`      | `POST` | Logout the current user and revoke their token                                                      |
| `/cart`             | `GET`  | Get the current user's shopping cart                                                                |
| `/cart/add`         | `POST` | Add a new item to the current user's shopping cart                                                   |
| `/cart/remove/:id`  | `POST` | Remove an item from the current user's shopping cart                                                 |
| `/order`            | `GET`  | Get the current user's order history                                                                 |
| `/order/new`        | `POST` | Create a new order for the current user                                                              |
| `/product`          | `GET`  | Get a list of all available products                                                                 |
| `/product/:id`      | `GET`  | Get a specific product by ID                                                                         |
| `/stripe/charge`    | `POST` | Process a payment using Stripe                                                                       |
| `/verifyToken`      | `POST` | Verify the current user's authentication token and retrieve their user information                   |


## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.
