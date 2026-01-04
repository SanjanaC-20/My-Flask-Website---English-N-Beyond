# My-Flask-Website---English-N-Beyond
A Flask-based English tutorial website for new students, introducing the institute and contact info.

## 🔧 Recent improvements
- **Routes added:**
  - `GET /` → renders `templates/index.html` (Index)
  - `GET /home` → renders `templates/home.html` (Home)
  - `GET /about` → renders `templates/about.html` (About)
- **Navigation menu:** a site menu was added to `templates/index.html` with links to **Index**, **Home**, **About**, and **Contact**; the logo now links to `/`.
- **Static assets:** CSS link spacing in `index.html` was fixed (`{{ url_for('static', filename='style.css') }}`).
- **Note:** the `/contact` link exists in the navigation but a `/contact` route/template is not yet implemented.

## ▶️ Run locally
1. Install dependencies:
```bash
python -m pip install flask
```
2. Run the app:
```bash
python app.py
```
3. Visit these pages in your browser:
- http://localhost:5000/  (Index)
- http://localhost:5000/home (Home)
- http://localhost:5000/about (About)

## 📂 Project structure (key files)
- `app.py` — Flask application and routes
- `templates/` — HTML templates: `index.html`, `home.html`, `about.html`
- `static/` — static files (CSS, images)

---

If you'd like, I can add a `/contact` route and a `contact.html` template or add a site-wide nav include to keep the menu consistent across pages.
