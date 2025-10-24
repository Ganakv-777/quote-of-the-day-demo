# Inspirational Quote Web App

## Overview
A minimal single-page web app that fetches and displays a random inspirational quote from the Quotable API. It loads a quote on page open and lets you fetch a new one with a button.

## Setup
- No build tools required.
- Option 1: Double-click index.html to open it in your browser.
- Option 2: Serve it with any static server (recommended for consistent behavior):
  - Python: python3 -m http.server 8000
  - Node (serve): npx serve .
  - Then open http://localhost:8000 in your browser.

## Usage
- The page automatically fetches an inspirational quote on load.
- Click “New Quote” to fetch another random inspirational quote.
- If a network error occurs, an error message will be shown; click the button to try again.