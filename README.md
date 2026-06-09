# VocabReview
Simple English vocabulary learning app.

## Running Locally

Because the application dynamically loads `vocab.csv`, modern web browsers will restrict opening the `index.html` file directly via `file://` protocols due to CORS security policies.

To run the application locally, start a simple static web server in this directory:

### Option 1: Node.js (recommended)
If you have Node.js installed, run:
```bash
npx serve .
```
Then open the address printed in the terminal (usually `http://localhost:3000` or `http://localhost:5000`).

### Option 2: Python
If you have Python installed, run:
```bash
python -m http.server 8000
```
Then open `http://localhost:8000` in your web browser.

### Option 3: VS Code Live Server
If using VS Code, you can install the **Live Server** extension and click **Go Live** in the status bar to run the app.

