# Mathgames

A lightweight webpage that embeds the PawBorough game.

## Run locally

Open `index.html` in a browser, or serve the directory with any static web server:

```bash
python3 -m http.server
```

Then visit <http://localhost:8000>.

## Deploy

This is a static site and can be hosted with GitHub Pages. In the repository settings, enable Pages and select the branch containing `index.html` as the deployment source.

## Notes

- The embedded game is loaded from `https://pawborough.net/`.
- The iframe uses `sandbox="allow-scripts"`, so the embedded site may require additional sandbox permissions if its features need them.
- If the game does not load, the source site may prevent embedding with its security headers.
