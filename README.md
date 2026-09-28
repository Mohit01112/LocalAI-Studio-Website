# LocalAI Studio Website (Flask + HTML)

A responsive product landing page for LocalAI Studio, built with Python Flask, HTML, and CSS.

## Project structure
- `app.py` — Flask server and homepage route
- `templates/index.html` — page markup
- `static/style.css` — responsive styling

## Run locally
```bash
python -m venv .venv
.venv\\Scripts\\activate
pip install -r requirements.txt
python app.py
```
Then open http://127.0.0.1:5000

## Production
Set `debug=False` before deploying. The Download buttons point to the project's GitHub Releases page; publish installer assets there before promoting downloads.
