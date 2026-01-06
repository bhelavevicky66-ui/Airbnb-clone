# Staybnb — Static E-commerce / Listings Website

A small static website template inspired by Airbnb — includes listing pages (`second.html`), a house detail page (`house.html`), and a responsive footer and filter sidebar.

## ⚡ Key features

- Responsive layout with a grid-based footer and filter sidebar
- Centered footer content on small screens (mobile) and centered filter panel on tablet/mobile
- Simple, static HTML/CSS (no bundlers or servers required)
- Images located in the `images/` folder

## 📁 Project structure

- `index.html` — Home / landing
- `house.html` — House / details page
- `second.html` — Listings page with filters sidebar
- `style.css` — Main styles
- `footer.css` — Footer styles
- `images/` — Image assets

## 🚀 How to run locally

1. Open any of the `.html` files directly in a browser (double-click or drag into browser).

OR

2. For a live-reload dev server (recommended when editing):
   - Install VS Code Live Server extension and click "Go Live", or
   - Install `live-server` globally and run:
     ```bash
     npm i -g live-server
     live-server
     ```

## 📱 Responsive testing

- Open DevTools (F12) and toggle device toolbar (Ctrl+Shift+M).
- Useful breakpoints to test:
  - ≤ 743px: footer sections and filter panel stack and center
  - ≤ 480px: footer columns and headings centered, filter becomes full-width

## ✍️ Customization / Tips

- Footer styles: `footer.css`
- General layout and sidebar: `style.css`
- To change spacing, update breakpoints in the media queries inside those files.

## 🤝 Contributing

Feel free to open issues or send pull requests to add features (mobile accordion for filters, animations, or accessibility improvements).

## 📄 License

MIT — see `LICENSE` (or add one if you want to publish this project).

---

If you'd like, I can add: screenshots, a short demo GIF, or a small `CONTRIBUTING.md` with instructions on how to add features. Tell me what you'd like to include next.