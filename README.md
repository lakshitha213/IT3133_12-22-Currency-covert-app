# Currency Converter App

A simple and responsive currency converter application built with React Native and the React Native Paper UI library. This app allows users to convert an amount from one currency to another using exchange rate data from a public API.

## Features

- **Currency Conversion**: Convert an entered amount from one currency to another.
- **Dynamic Inputs**: Update the base and target currencies dynamically.
- **Real-Time Exchange Rates**: Fetch the latest exchange rates from an API.
- **Responsive Design**: Optimized for various device sizes using React Native.

---

## Tech Stack

- **Frontend**: React Native
- **UI Framework**: React Native Paper
- **HTTP Client**: Axios
- **API Used**: [ExchangeRate-API](https://www.exchangerate-api.com/)

---

## Installation and Setup

### Prerequisites

1. **Node.js** and **npm**: Ensure you have [Node.js](https://nodejs.org/) installed.
2. **React Native Environment**: Set up the React Native development environment for your operating system ([React Native Setup](https://reactnative.dev/docs/environment-setup)).

### Steps

1. **Clone the Repository**

   ```bash
   git clone https://github.com/your-repo/currency-converter-app.git
   cd currency-converter-app
   ```
2. **Navigate to the project directory:**
 
   ```
   cd currency-converter-app
   ```
3. **Install the dependencies:**

   ```
    npm install
   ```
4. **Run the App on an Emulator or Physical Device**

   ### For Android:

   To run the app on an Android device or emulator, use the following command:

   ```bash
   npx react-native run-android
   ```
   ### For iOS:

   To run the app on an iOS device or simulator, use the following command:

   ```bash
   npx react-native run-ios
   ```
## API Used

This app fetches real-time exchange rates using the [ExchangeRate-API](https://www.exchangerate-api.com/).

Make sure to replace the URL with your API key or use a different API if needed.

## How It Works

1. The user enters an amount and selects the source and target currencies.
2. When the user presses the "Convert" button, the app fetches the current exchange rate between the two currencies.
3. The conversion result is displayed on the screen.

## Code Overview

- **App.js**: The main file containing the app's core logic, including state management, API call for exchange rates, and UI components.
- **react-native-paper**: A library used for UI components (e.g., `TextInput`, `Button`, `Text`).
- **axios**: A promise-based HTTP client used to make requests to the currency exchange API.

## Styling

The app uses basic styling with `react-native-paper` components and custom styles defined in `styles`.

### Styling Notes

- The input fields have an orange background with a blue border.
- The button has a red background with white text.
- The result text is displayed in blue with a bold font weight.

## Contribution

Feel free to fork this repository and submit pull requests for improvements or fixes. Contributions are always welcome!
   
   
