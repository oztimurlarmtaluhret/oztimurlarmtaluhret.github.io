# UHRET official website

The bilingual, single-page website of the Hackathon, Robotics and Electronics Community at Öztimurlar Vocational and Technical Anatolian High School.

The site is built with semantic HTML, CSS and a small amount of vanilla JavaScript. It has no build step or external dependencies and is served directly by GitHub Pages.

## Local preview

Run a static server from the repository root:

```sh
python3 -m http.server 4173
```

Then open `http://localhost:4173/`.

## Structure

- `index.html`: content and page structure
- `css/style.css`: visual system and responsive layouts
- `js/main.js`: TR/EN switching and mobile navigation
- `CNAME`: custom-domain configuration for GitHub Pages
