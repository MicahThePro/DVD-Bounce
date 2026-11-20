# 📀 DVD Bounce

Relive the classic DVD screensaver in your browser. Watch the logo bounce off the edges, change colors every time it hits a wall, and click anywhere to launch a brand-new one!

**[▶️ Try it live](https://micahthepro.github.io/DVD-Bounce)**

## ✨ Features

- 🟦 **Bouncing logo:** The DVD logo glides around the screen and bounces off every edge.
- 🌈 **Color changes:** Each bounce gives the logo a fresh random color.
- 🖱️ **Click to spawn:** Click anywhere to launch another logo moving in a random direction.
- 🎞️ **Smooth motion:** Movement is tied to real time, so it runs at the same speed on any monitor.
- 📱 **Fits any window:** Logos stay on screen when you resize the window.
- 🔖 **Custom favicon:** The browser tab shows a DVD-style icon.

## 🛠️ Built With

- HTML
- CSS
- JavaScript (no libraries, no build step)

## 🚀 Running It Locally

You only need a web browser. If you'd like to run it from a local server, here's how:

1. Clone or download this repository.
2. Open a terminal in the project folder.
3. Start a simple server with Python:
   ```bash
   python -m http.server 8000
   ```
4. Open [http://localhost:8000](http://localhost:8000) in your browser.

Or just double-click `index.html` to open it directly.

## 📁 Project Structure

```
DVD-Bounce/
├── index.html      # The whole app: markup, styles, and logic
├── dvd-logo.svg    # The DVD logo
├── favicon.svg     # The browser tab icon
└── README.md
```

## 🤝 Want to Tweak It?

Everything lives in `index.html`. Some easy things to try:

- Change `SPEED` to make the logos faster or slower.
- Change `LOGO_WIDTH` to make the logos bigger or smaller.
- Change the `background-color` in the CSS to something other than black.

Have fun, and click a lot! 🎉
