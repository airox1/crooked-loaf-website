# Crooked Loaf 🍞

> Artisan bakery & coffee shop website — HTML/CSS/JS with menu, gallery, booking form, and FAQ.

A fully static, single-file website built for **Crooked Loaf**, a fictional artisan bakery and coffee shop. Designed as a portfolio piece to demonstrate professional web design for local food businesses.

---

## Live Site

🌐 [View on GitHub Pages](https://yourusername.github.io/crooked-loaf-website/)

---

## Features

- **Hero section** — split layout with animated headline and stats
- **Our Story** — brand values displayed in a 2×2 card grid
- **Menu** — tabbed interface across Bakery, Pastries, and Drinks
- **Gallery** — 5-panel mosaic with hover reveal labels
- **Booking form** — reservation form with confirmation state
- **Contact & FAQ** — 3-column contact cards and accordion FAQ
- **Fully responsive** — mobile-friendly layout

---

## Tech Stack

- Pure HTML, CSS, and vanilla JavaScript
- No frameworks, no dependencies
- Google Fonts: Playfair Display, Lora, DM Sans
- Hosted via GitHub Pages

---

## Project Structure

```
crooked-loaf-website/
├── index.html        # Main site file
├── images/           # Photo assets (add your own here)
└── README.md
```

---

## Adding Your Own Photos

The site is set up to use local image files. To swap in real photos:

1. Add your images to the `images/` folder
2. In `index.html`, find any `<img>` tag or emoji placeholder
3. Update the `src` attribute to point to your file, e.g. `src="images/sourdough.jpg"`

Free high-quality food photography available at [Unsplash](https://unsplash.com) and [Pexels](https://pexels.com).

---

## Running Locally

No build step needed. From your terminal:

```bash
python3 -m http.server 8080
```

Then open `http://localhost:8080` in your browser.

---

## Deployment

This site is deployed via **GitHub Pages**.

To deploy your own version:
1. Fork or clone this repo
2. Go to **Settings → Pages**
3. Set source to `main` branch, `/ (root)`
4. Your site will be live at `https://yourusername.github.io/crooked-loaf-website/`

---

## License

This project is for portfolio and demonstration purposes. Feel free to use it as a template for client work.
