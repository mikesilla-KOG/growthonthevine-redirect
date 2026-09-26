# growthonthevine-redirect

Forwards the old domain **growthonthevine.com** to **https://growonthevine.com**, keeping path, query and hash.

- `index.html` handles `/`; `404.html` handles every deep path (e.g. `/clips/word-turns-a-nation/`).
- JS `location.replace` does the path-preserving redirect; the meta refresh is a no-JS fallback (goes to the home page).
- Main site repo: [mikesilla-KOG/growth-on-the-vine](https://github.com/mikesilla-KOG/growth-on-the-vine).
