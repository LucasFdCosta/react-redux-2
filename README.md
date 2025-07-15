## Project Description

Small React project about simple Redux concepts

## Table of Contents

- [Prerequisites](#prerequisites)
- [Installation](#installation)
- [Usage](#usage)
- [Features](#features)
- [Concepts](#Concepts)

## Prerequisites
- [Node.js](https://nodejs.org/en/)
- [NPM](https://www.npmjs.com/)

## Installation

1. Clone the repo:
    ```bash
    git clone https://github.com/LucasFdCosta/coffee-delivery.git
    ```
2. Navigate into the project directory:
    ```bash
    cd react-redux-2
    ```
3. Install dependencies:
    ```bash
    npm install
    ```
4. Start the development server:
    ```bash
    npm run start
    ```
5. Start the local instance of the json-server:
    ```bash
    npm run dev:server
    ```

## Usage

To use the application, follow the instructions above. You may encounter an error when trying to run both ```npm run start``` and ```npm run dev:server``` because of port conflict, you can just answer "Yes" to any request of changing the port to any port available and open it to see the application. Then open your web browser and go to `http://localhost:{YOUR_APP_PORT}`.

## Features

- Listing items
- Add items to the cart
- Increase or decrease the number of items in the cart

## Concepts
- React
- Redux
  - Handling Async Tasks with Redux
  - Where to put the code