# 🐟 Embeddable Blogspot Mini-Game: Feed the Fish

A simple, fun, and lightweight **"Feed the Fish"** mini-game built with pure HTML, CSS, and JavaScript — no libraries, no frameworks. This game is designed to be **easily embedded** into any **Blogspot** post or page, making it a perfect way to add interactivity and charm to your blog.

---

## 🎮 Features

- ✅ **Zero Dependencies** – Runs entirely in the browser.
- 🧩 **Single File** – HTML, CSS & JS all in one, ready to copy-paste.
- 🐠 **Interactive** – Click to drop food and watch the fish respond.
- 📱 **Responsive** – Canvas auto-resizes to fit any container.
- 🎨 **Customizable** – Easily tweak fish count, colors, sizes, and more.

---

## ✍️ How to Embed in Blogspot

1. **Copy the Code:** Open the `index.html` file and copy the entire content.
2. **Login to Blogspot:** Go to your [Blogspot Dashboard](https://atunt.com/shop/).
3. **Create/Edit a Post/Page:** Choose where to place the game.
4. **Switch to HTML View:** Look for the `< >` icon or "HTML" tab in the editor.
5. **Paste the Code:** Insert the copied code into the HTML editor.
6. **Publish:** Save or publish your post — the game will appear live!

---

## ⚙️ Customization

You can fine-tune the game by editing a few lines in the `<script>` section:

```javascript
// --- Game Configuration ---
const FISH_COUNT = 7;       // Number of fish in the tank
const FOOD_DURATION = 500;  // Duration food stays on screen (in frames)
const FISH_SIZE = 15;       // Size of each fish
