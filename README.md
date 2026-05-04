# Polimerase EJ

Multi-page static website for Polimerase EJ - Consultoria especializada em rotulagem nutricional, rotulagem cosmética, minicursos e palestras para o setor farmacêutico e alimentício.

## 🌐 Website

Visit the live site: https://juliamondt.github.io/polimerasejr

## 📁 Project Structure

```
├── index.html           # Home page
├── sobre.html           # About page
├── servicos.html        # Services page
├── portfolio.html       # Portfolio page
├── blog.html            # Blog page
├── equipe.html          # Team page
├── faq.html             # FAQ page
├── contato.html         # Contact page
├── style.css            # Global stylesheet
└── build_site.py        # Python script to build the site
```

## 🛠️ Development

This is a static multi-page site with no build system. To preview changes:

```bash
python3 -m http.server 8000
```

Then open `http://localhost:8000` in your browser.

## 📄 Building the Site

Run the build script to generate all HTML pages from `old-index.html`:

```bash
python3 build_site.py
```

This creates all HTML pages with proper navigation, footer, and WhatsApp button.
