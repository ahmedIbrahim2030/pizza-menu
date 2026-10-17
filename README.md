# Pizza Menu

A modern React-based pizza menu application that showcases a curated selection of pizzas with ingredient details, pricing, and availability status. The app is designed as a clean, restaurant-style interface and serves as a simple demonstration of core React concepts such as component composition, data-driven rendering, and conditional styling.

## Overview

This project displays a menu of pizzas using a structured data model and renders each item as a card with:

- Pizza name
- Description of ingredients
- Price
- Image
- Sold-out indicator when applicable

It is ideal for learning front-end development patterns or as a starting point for a real restaurant ordering interface.

## Features

- Responsive restaurant-style layout
- Reusable menu item components
- Dynamic rendering from a central data source
- Sold-out items visually marked as unavailable
- Clean and minimal styling for an appealing UI

## Tech Stack

- React
- JavaScript
- CSS
- Create React App

## Project Structure

```text
pizza-menu/
├── public/                 # Static assets and HTML template
├── src/
│   ├── App.js              # Main application component
│   ├── App.css             # App styles
│   ├── data.js             # Pizza menu data
│   ├── index.js            # React entry point
│   └── index.css           # Global styles
├── package.json            # Project metadata and scripts
├── README.md               # Project documentation
├── .gitignore
└── public/                 # Static files
```

## Getting Started

### Prerequisites

Make sure you have the following installed:

- Node.js (v18 or later recommended)
- npm

### Installation

```bash
npm install
```

### Run the app locally

```bash
npm start
```

This starts the development server and opens the app in your browser at:

```text
http://localhost:3000
```

### Build for production

```bash
npm run build
```

This creates an optimized production build in the `build/` directory.

## Available Scripts

```bash
npm start
npm test
npm run build
npm run eject
```

- `npm start` — launches the app in development mode
- `npm test` — runs the test suite
- `npm run build` — creates a production build
- `npm run eject` — exposes the underlying Create React App configuration

## Data Model

The menu content is stored in `src/data.js` as an array of pizza objects. Each object contains information such as:

- `name`
- `ingredients`
- `price`
- `photoName`
- `soldOut`

This structure makes it easy to expand the menu with new items or modify existing entries.

## Learning Purpose

This project is a beginner-friendly React application designed to demonstrate:

- JSX rendering
- Component-based UI design
- Data-driven lists
- State and conditional rendering fundamentals
- CSS styling in React applications
