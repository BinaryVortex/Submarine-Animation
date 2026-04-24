# Submarine Animation

A lightweight, eye-catching submarine animation built with plain HTML and CSS (with minimal JavaScript). This single-file demo presents a submarine cruising across the screen with a subtle bobbing motion and rising bubbles — perfect as a visual toy, a CSS learning example, or a decorative element for a web page.

![Submarine Animation Preview](./Screenshot%202024-08-25%20182620.png)

## Demo

Open `index.html` in any modern browser to see the animation. No build tools required.

Quick ways to run the demo:

- Double-click `index.html` in the repository folder.
- Serve the folder locally (recommended):

  npx http-server .

  Then visit the URL shown by the server (usually `http://localhost:8080`).

## Features

- Pure CSS keyframe animations for movement, bobbing, and bubbles.
- Lightweight: one HTML file and one CSS file.
- Easy to customize colors, speed, and the number of bubbles.
- Works on modern desktop and mobile browsers.

## How it works (short)

- index.html contains the markup for the submarine, bubbles, and sea/sky layers.
- style.css defines CSS variables, the submarine styling, and multiple keyframe animations:
  - horizontal travel across the viewport
  - subtle vertical bobbing
  - bubble rise and fade animations

The visual effect is achieved entirely with CSS transforms and animation timing functions; JavaScript is not required for the core animation.

## Customization tips

- Change colors: edit the CSS variables or the `.submarine`/`.sea` rules in `style.css`.
- Adjust speed: modify the `animation-duration` values in `style.css` (look for `submarine` and `bubble` animations).
- Add more bubbles: copy the bubble markup in `index.html` and adjust their `animation-delay` values to stagger them.
- Make the submarine larger/smaller by scaling the `.submarine` container and adjusting related sizing variables.

## Files

- `index.html` — demo page and markup
- `style.css` — styles and keyframe animations
- `Screenshot 2024-08-25 182620.png` — preview image used in this README

## Development

This demo has no build step. Edit the files and refresh your browser to see changes. For a faster edit-refresh cycle, use a static server with live-reload (e.g., the Live Server extension in VS Code).

## License

This project is released under the MIT License. Feel free to copy, modify, and use it in your own projects. If you want me to add a LICENSE file, I can create one for you.

## Credits

Built by BinaryVortex. Thanks for checking out the demo — improvements and pull requests are welcome. If you'd like, I can also:

- Add a hosted demo (GitHub Pages) and update the README with a live link.
- Replace the screenshot with an animated GIF recording of the demo.

