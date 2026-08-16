# Backend Integration

Front-end application for product management with backend API integration using JavaScript Fetch API.

## About the Project

This project is a front-end application developed with HTML, CSS, and JavaScript, focused on demonstrating backend integration through asynchronous HTTP requests using the native Fetch API.

The application communicates with a REST API to list, create, and manage products dynamically, without page reloads.

## Table of Contents

- [Architecture](#architecture)
- [Project Structure](#project-structure)
- [Technologies](#technologies)
- [How to Run](#how-to-run)

## Architecture

The project follows a simple front-end structure with clear separation between presentation and data communication:

- **HTML:** Defines the page structure and user interface components.
- **CSS:** Responsible for styling and visual presentation.
- **JavaScript:** Handles API communication, DOM manipulation, and application logic.

## Project Structure

```
├── index.html              # Main page and UI structure
├── gerenciarProdutos.js    # Product management logic and API requests
└── styles.css              # Application styling
```

## Technologies

- **Language:** JavaScript (ES6+), HTML5, CSS3
- **API Communication:** Fetch API (native browser)
- **Principles:** Separation of concerns, asynchronous programming

## How to Run

1. Clone the repository:

```bash
git clone https://github.com/Dimitri-YermiaK/BackendIntegration.git
```

2. Navigate to the project directory:

```bash
cd BackendIntegration
```

3. Open `index.html` directly in your browser.

> **Note:** A running backend API is required for the application to work correctly. Make sure the API is available before using the product management features.
