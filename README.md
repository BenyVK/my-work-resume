# Benyamin.Gharri.ir

A single-page, print-friendly online resume / CV for **Benyamin Gharri** — Web & Software Developer.

🔗 Live: [Benyamin.Gharri.ir](https://benyamin.gharri.ir)

## ✨ Features

- Clean, document-style resume layout (sections: Skills, Experience & Projects, Contact)
- "Download / Print as PDF" button (uses the browser's native print dialog)
- Custom typography powered by the self-hosted **EB Garamond** font family
- Minified and original (`.org`) versions of the CSS/HTML included for easy editing
- No build step, no dependencies — pure HTML & CSS

## 📁 Project Structure

```
Benyamin.Gharri.ir/
├── index.html          # Production (minified) page
├── index.org.html      # Readable/original source page
├── style.min.css        # Production (minified) styles
├── style.org.css        # Readable/original styles
├── fonts.min.css         # Minified font-face declarations
├── fonts.org.css         # Original font-face declarations
├── EB_Garamond/          # Self-hosted EB Garamond font files (.ttf)
└── img/
    ├── wikipedia.png     # Favicon
    └── index.html     # Back to ../index.html
```

## 🚀 Usage

This is a static website — no build tools or server-side code required.

1. Clone or download this repository.
2. Open `index.html` directly in your browser, **or**
3. Serve the folder with any static file server, e.g.:

   ```bash
   npx serve .
   # or
   python3 -m http.server
   ```

To make edits, work with the `.org` (original) files (`index.org.html`, `style.org.css`, `fonts.org.css`) and re-minify before deploying.

## 🖋️ Fonts

This project uses the [EB Garamond](https://github.com/octaviopardo/EBGaramond12) typeface, self-hosted under the `EB_Garamond/` directory and loaded via `fonts.min.css` / `fonts.org.css`. EB Garamond is licensed separately under the SIL Open Font License (OFL) — see the font's own license terms for details.

## 📬 Contact

- **Email:** benyamin@gharri.ir
- **GitHub:** [github.com/BenyVK](https://github.com/BenyVK)
- **Telegram:** [t.me/i36VK](https://t.me/i36VK)
- **Telegram Channel:** [t.me/OpenSAMP](https://t.me/OpenSAMP)

## 📄 License

No license is required for this project and you can use this code.

## Close Page
