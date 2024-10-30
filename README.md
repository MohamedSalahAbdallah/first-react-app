# Random Advice App

This is a simple React application that fetches and displays random pieces of advice. Users can click a button to get new advice, and the app keeps track of how many pieces of advice have been read.

## Features

- Fetches random advice from an external API
- Displays the advice on the screen
- Allows users to request new advice with a button click
- Keeps count of how many pieces of advice have been read

## Technologies Used

- React
- JavaScript (ES6+)
- Fetch API for making HTTP requests

## Getting Started

To run this project locally:

1. Clone the repository
2. Navigate to the project directory
3. Install dependencies:
4. Start the development server:
5. Open your browser and visit `http://localhost:3000`

## How It Works

The main `App` component uses React hooks (`useState` and `useEffect`) to manage state and side effects:

- `useState` is used to store the current advice and the count of advice pieces read.
- `useEffect` is used to fetch initial advice when the component mounts.
- The `getAdvice` function fetches new advice from the API and updates the state.
- A button allows users to request new advice on demand.

The `Message` component displays the count of advice pieces read.

## API Used

This app uses the [Advice Slip JSON API](https://api.adviceslip.com/) to fetch random advice.

## License

[MIT](https://choosealicense.com/licenses/mit/)
