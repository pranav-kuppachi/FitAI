# FitAI

A desktop fitness and nutrition application built with Electron, JavaScript, HTML and CSS.

FitAI is website based on basic fitness tracking, nutrition information, recipes and user profiles all together in one desktop application.

## Features

* **User Profiles** - Create and manage individual fitness profiles.
* **Activity Tracking** - Record and keep track of fitness activity.
* **Fitness Dashboard** - View activity and fitness information in one place.
* **Recipe Search** - Search for recipes using the Spoonacular API.
* **Nutrition Information** - Get nutritional information for food and recipes.
* **Diet Tracking** - Keep track of diet related information alongside fitness activity.
* **Local Data Storage** - Store application data locally using JSON files.
* **Authentication** - Basic user authentication and profile management.
* **Desktop Application** - Packaged as an Electron application rather than a browser-only website.

## Tech Stack

* **Electron.js** - Desktop application framework
* **JavaScript** - Application logic
* **HTML / CSS** - User interface
* **Node.js** - Runtime and Electron backend functionality
* **Chart.js** - Data visualization
* **Spoonacular API** - Recipe and nutrition data
* **JSON** - Local data persistence

## How It Works

FitAI is built around a simple flow:

1. A user creates or accesses their profile.
2. Fitness and personal information is stored locally.
3. The dashboard brings together the user's activity and fitness data.
4. Users can search for recipes and nutrition information through the Spoonacular API.

## Project Structure

The project is organized as an Electron application with the frontend handling the user interface and JavaScript/Node.js handling application functionality and data operations.

## Running Locally

### Prerequisites

* Node.js
* npm

### Installation

Clone the repository:

```bash
git clone https://github.com/pranav-kuppachi/FitAI.git
cd FitAI
```

Install dependencies:

```bash
npm install
```

Start the application:

```bash
npm start
```

> The exact start command may differ depending on the scripts currently defined in `package.json`.

## What I Built

This project was built to explore how a desktop application can combine fitness tracking and nutrition features into a single interface.

The main focus was on working with Electron, managing application state and local data, integrating an external API and building a complete user facing application rather than a collection of isolated features.

## License

This project is for educational and portfolio purposes.
