# React Advice App

## Overview

This is a simple React application that fetches random advice from the [Advice Slip API](https://api.adviceslip.com/) and displays it. The app also keeps track of the number of advice pieces read.

## Features

- Fetches random advice from the API
- Displays advice on the main screen
- Keeps track of the number of advice pieces read
- Allows the user to manually fetch new advice

## Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/your-username/react-advice-app.git
   cd react-advice-app
   ```  

2. Install dependencies:

    ```bash
    npm install
    ```
3. Start the development server:

    ```bash
    npm start
    ```
    The app will be accessible at http://localhost:3000.


## Usage

1. Open the app in your browser.

2. The main screen displays a random piece of advice.

3. Click the "Get advice" button to fetch a new piece of advice.

4. The count of advice pieces read is displayed below the advice.

Feel free to explore and enjoy the wisdom!

## Code Structure

- `App.js`: The main component responsible for fetching and displaying advice.
- `Message.js`: A simple component displaying the count of advice pieces read.

## Dependencies

- React: v16.0+
- [Advice Slip API](https://api.adviceslip.com/): Used for fetching random advice.
