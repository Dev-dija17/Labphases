# Personal Book Library (PrjFinal)

Simple client-side app to manage a personal book library with a small login mock and a responsive pink/beige/white UI.

## Features
- Login mock (index.html) → redirects to home.html on success
- Add / delete books, change reading status, rate completed books
- Responsive layout using CSS Grid
- Data persisted in browser localStorage

## Files
- index.html — Login page
- home.html — Main app (add books, view/filter, rate, delete)
- style.css — Vanilla CSS (pink / beige / white palette)
- README.md — this file

## Run (Windows)
- Double-click `index.html` to open in your browser
- Or run a simple static server from the project folder:
  - With Python: `python -m http.server 5500`
  - With Node (npx): `npx http-server -p 5500`
  Then open http://localhost:5500/index.html

## Notes
- Books are stored in `localStorage` under key `myLibrary`.
- To reset data: open DevTools → Application → Local Storage → remove `myLibrary`, or run `localStorage.removeItem('myLibrary')` in console.
- UI palette: pink / beige / white

## Known issues & TODO
- Login is a client-side mock (not secure) — replace with real auth for production
- Improve accessibility (focus states, ARIA)
- Add validation and better error handling

## License
Unlicensed — use and modify as needed.