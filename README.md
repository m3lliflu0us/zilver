# Busrit Passenger Management

This project is a Vue.js web application designed to manage a list of passengers for a bus ride. It allows users to add new passengers, remove specific ones, shuffle the order, and remove all passengers with a smooth UI experience.

## Features

- **Add Passengers**: Add a new passenger to the list with a unique ID and name.
- **Remove Passenger**: Remove a passenger by their number in the list.
- **Remove Fifth Passenger**: Specifically remove the fifth passenger from the list.
- **Shuffle Passengers**: Randomly shuffle the order of the passengers.
- **Remove All Passengers**: Clear the entire list of passengers.

## Installation

To run this project locally, you'll need to have Vue.js installed. You can include Vue via a CDN as shown in the HTML file or install it via npm.

## Usage

1. Open the `index.html` file in a web browser.
2. Use the input fields and buttons to manage the passenger list.

## Styling

The application comes with a predefined set of CSS styles for a pleasant visual experience, including custom scrollbar styles and animations for adding/removing passengers.

## Vue Instance

The Vue instance is initialized with the following data properties and methods:

- `newPassengerName`: Holds the name for a new passenger to be added.
- `passengerNumber`: Holds the number of the passenger to be removed.
- `passengers`: An array of passenger objects.

The methods include `addPassenger`, `removePassenger`, `removeFifthPassenger`, `shufflePassengers`, and `removeAllPassengers`, each corresponding to the features listed above.