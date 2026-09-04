# MDC | Meta Developer Community

Official landing page for the **Meta Developer Community (MDC)** — GITAM Visakhapatnam. A community of developers, designers, and innovators building real-world projects and growing together.

## 🌐 Live Preview

Open `index.html` in any browser, or [enable GitHub Pages](#deploying-with-github-pages) to view it live at:
`https://<your-username>.github.io/<repo-name>/`

## 📁 Project Structure

```
mdc-website/
├── index.html          # Home page (hero, highlights, join)
├── about.html          # About page (story, mission, values, stats)
├── css/
│   ├── style.css         # Shared base styles: variables, navbar, hero, highlights, join, footer
│   └── about.css         # About-page-only styles — @imports style.css, then adds its own rules
├── images/               # (optional) logo/screenshots — currently empty
├── .gitignore
└── README.md
```

> **CSS setup:** `index.html` links to `css/style.css`. `about.html` links to `css/about.css`, which starts with `@import url('style.css');` to pull in the shared base styles, then layers on About-page-only rules (`.page-hero`, `.about-section`, `.values-grid`, `.stats-block`, `.cta-button-dark`). Keep both files in the `css/` folder together, since `about.css` depends on `style.css` being reachable at that relative path.

## ✨ Features

- Clean, responsive multi-page layout (Home + About)
- Custom color palette using CSS variables (`--navy`, `--blue`, `--steel`, `--light`, `--pale`, `--white`) — used consistently across both pages
- Home: Navbar, Hero, Highlights (Learn / Build / Connect), Join, Footer
- About: Page hero, Our Story, Our Mission, Values grid, Stats, Join CTA, Footer
- Shared navbar with working cross-page links (`Home`, `About`, `Join Us`)
- Mobile-friendly with a breakpoint at `600px`
- No frameworks or build tools — pure HTML & CSS

## 🎨 Color Palette

| Name  | Hex       |
|-------|-----------|
| Navy  | `#081F5C` |
| Blue  | `#334EAC` |
| Steel | `#7690D1` |
| Light | `#D0E3FF` |
| Pale  | `#E7F1FF` |
| White | `#F9FCFF` |

## 🚀 Getting Started

1. Clone the repository:
   ```bash
   git clone https://github.com/<your-username>/<repo-name>.git
   cd <repo-name>
   ```
2. Open `index.html` directly in your browser — no build step required.

## 📄 Deploying with GitHub Pages

1. Push this repo to GitHub.
2. Go to **Settings → Pages**.
3. Under **Source**, select the `main` branch and `/ (root)` folder.
4. Save — your site will be live at `https://<your-username>.github.io/<repo-name>/` within a minute or two.

## 🛠️ Tech Stack

- HTML5
- CSS3 (Flexbox, CSS variables, media queries)

## 🤝 Contributing

Pull requests are welcome! For major changes, please open an issue first to discuss what you'd like to change.

## 📜 License

© 2026 Meta Developer Community, GITAM Visakhapatnam. All rights reserved.
