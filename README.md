# Coursera Module 5 Solutions (HTML/CSS/JavaScript)

Solutions for **Coursera – Module 5** assignment.

This project is a small front-end web app that loads restaurant **categories** and **menu items** from a remote API and renders them dynamically using HTML snippet templates.

## Repository Structure

```text
.
├── index.html                # App entry point
├── css/                      # Stylesheets (Bootstrap + custom styles)
├── js/                       # JavaScript (app logic + helper libs)
├── snippets/                 # HTML partials injected dynamically
├── images/                   # UI images/assets
└── fonts/                    # Font assets (Bootstrap glyphicons)
```

## How It Works (High Level)
- The page shell is defined in `index.html`.
- The main content area (`#main-content`) is populated dynamically by `js/script.js`.
- HTML templates under `snippets/` are fetched and filled using placeholder substitution.
- Data is loaded from a remote endpoint (categories + menu items) via JS utilities.

## Run Locally
1. Download/clone the repository.
2. Open `index.html` in a browser.

> Note: Some browsers block AJAX requests from local files. If you see loading issues, run a local web server (e.g., VS Code Live Server) and open the served URL.

## Course/Assignment
- Coursera: Module 5
- Topic: HTML, CSS, JavaScript (dynamic rendering with JS and templates)
