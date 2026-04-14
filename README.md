# Arc Alter

Official website for **Arc Alter** — Technology Support, AI Integration, and Web Design services.

🌐 **Live site:** [arcalter.com](https://arcalter.com)

---

## About

Arc Alter helps businesses navigate the digital landscape with expert technology support, intelligent AI solutions, and web experiences that convert visitors into clients.

**Services:**
- Technology Support — IT management, troubleshooting, infrastructure
- AI Integration — Chatbots, automation, data analysis
- Web Design — Fast, conversion-focused websites

---

## Project Structure

```
arc-alter/
├── index.html        # Main site (single-page)
├── style.css         # Design tokens, component styles
├── base.css          # CSS reset and base defaults
└── assets/
    └── logo.jpg      # Arc Alter logo
```

---

## Development

This is a static HTML/CSS/JS site — no build step required.

To run locally:

```bash
# Option 1: Python (built-in)
python3 -m http.server 3000

# Option 2: Node serve
npx serve . -l 3000
```

Then open [http://localhost:3000](http://localhost:3000).

---

## Deployment

The site is deployed via **Cloudflare Pages**. Every push to the `main` branch automatically triggers a new deployment.

---

## Updating the Site

To update content, edit `index.html`. To update styles, edit `style.css`. Push changes to `main` and Cloudflare Pages will redeploy automatically.

---

## Contact

For questions about the website, contact [hello@arcalter.com](mailto:hello@arcalter.com).
