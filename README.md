# Personal Portfolio

A clean, responsive personal portfolio built with HTML and CSS to showcase projects, skills, and contact details.

## Demo
- Live demo: (add your GitHub Pages or live URL here)

## Features
- Responsive layout (mobile-first)
- Hero / introduction section
- Projects / portfolio gallery
- Skills & tools section
- About me section
- Contact form or contact details
- Smooth navigation and accessible semantics
- Lightweight — no JavaScript required (HTML & CSS only)

## Built with
- HTML5
- CSS3 (Flexbox, Grid, CSS variables)
- Accessible semantic markup
- Optional: Sass or CSS preprocessor if you choose to extend

## Getting started

To view locally:
1. Clone the repo:
   ```
   git clone https://github.com/awexa-web/NCC-web-dev-task2.git
   ```
2. Open `index.html` in your browser, or serve with a simple HTTP server:
   ```
   # Python 3
   python -m http.server 8000
   # then open http://localhost:8000
   ```

## Folder structure
Example structure — update if your repo differs:
```
/
├─ index.html
├─ about.html
├─ projects.html
├─ contact.html
├─ css/
│  └─ styles.css
├─ assets/
│  ├─ images/
│  └─ icons/
└─ README.md
```

## How to customize
- Replace headings and copy in the HTML files with your name, bio, and project descriptions.
- Update project cards: change thumbnails in `assets/images/` and project links.
- Theme colors: change CSS variables at the top of `css/styles.css` (e.g., --primary, --accent).
- Fonts: include Google Fonts or local fonts in the `<head>` of your HTML.
- Add meta tags for SEO and social previews (Open Graph / Twitter Cards) in `index.html`.

## Accessibility & performance tips
- Use semantic elements (header, nav, main, section, footer).
- Provide `alt` text for images.
- Ensure color contrast meets WCAG AA.
- Optimize images (use compressed WebP/AVIF where possible).
- Keep CSS minimal and avoid render-blocking resources where possible.

## Deployment (GitHub Pages)
1. Push your code to the `main` branch.
2. In the repo on GitHub, go to Settings → Pages.
3. Select the `main` branch and `/` (root) as the folder, then save.
4. Your site will be available at `https://<username>.github.io/<repo>/` (or the custom domain you set).

## Contributing
Contributions are welcome. To propose changes:
1. Fork the repository.
2. Create a branch: `git checkout -b feat/your-change`
3. Commit your changes and push: `git push origin feat/your-change`
4. Open a pull request with a clear description of changes.

## License
This project is open source — add a license file (e.g., MIT) if you want to allow reuse.

## Contact
- Name: Your Name
- Email: your.email@example.com
- GitHub: https://github.com/your-username
- LinkedIn / Twitter: (add links)
