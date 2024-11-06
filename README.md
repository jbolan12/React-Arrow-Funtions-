# React-Arrow-Funtions-

# ES6 Arrow Functions - Emoji Dictionary

A React application demonstrating the usage of ES6 arrow functions to manipulate and display emoji data. This project uses arrow functions in mapping, filtering, and transforming data arrays to create a simple "emojipedia" dictionary.

## Table of Contents

1. [Overview](#overview)
2. [Installation](#installation)
3. [Usage](#usage)
4. [Features](#features)
5. [Technologies](#technologies)
6. [Scripts](#scripts)
7. [License](#license)

## Overview

The app renders a collection of emoji entries from a predefined dataset using ES6 arrow functions and React components. The emoji dictionary allows users to explore the meanings behind popular emojis and is an exercise in mapping data to reusable components in React.

## Installation

### Prerequisites

- Node.js (version 14 or above)
- npm (version 6 or above)

### Steps

1. Clone the repository:

   ```bash
   git clone https://github.com/jbolan12/React-Arrow-Funtions-.git

   Navigate to the project directory:

bash
cd your-repo

**Install the dependencies:**

bash
npm install

**Start the development server:**

bash
npm start
Open http://localhost:3000 in your browser to view the app.

## Usage
The application imports emojipedia.js, which contains emoji data, and uses ES6 .map() to render each emoji with its name and description. Additionally, ES6 functions (e.g., .filter(), .reduce()) are included as comments in index.js to illustrate various array manipulation methods.

**Example**
In emojipedia.js:

javascript

const emojipedia = [
  {
    id: 1,
    emoji: "💪",
    name: "Tense Biceps",
    meaning:
      "“You can do that!” or “I feel strong!” Arm with tense biceps. Also used in connection with doing sports, e.g., at the gym."
  },
  // Additional emojis...
];
export default emojipedia;


## Components
- App: The main component that maps over the emoji data to render each entry.
- Entry: A reusable component that displays an individual emoji’s icon, name, and description.


## Features
- Data Mapping with ES6 Arrow Functions: Uses .map() to dynamically generate emoji entries.
- Reusable Components: The Entry component acts as a reusable template for each dictionary entry.
- JavaScript Array Methods: Includes examples of various array methods in comments (e.g., .map(), .filter(), .reduce()).


## Technologies
- React (v18.3.1)
- React DOM (v18.3.1)
- CSS for styling in styles.css

## Scripts
start: Runs the app in development mode with react-scripts start.
build: Builds the app for production with react-scripts build.
test: Runs the test suite with react-scripts test --env=jsdom.
eject: Ejects the app from Create React App configuration.


## License
This project is licensed under the MIT License.
