# 🎸 Printable Guitar Tablature Editor

A browser-based guitar tab writer that mirrors physical manuscript paper. Built with pure HTML, CSS, and JavaScript, it provides an intuitive grid-based editing experience optimized for US Letter page layouts and PDF exports.

---

## ✨ Features

- **Standard 2-Page Layout:** Formatted specifically for US Letter print dimensions (5 staves per page, 10 staves total).
- **Interactive Tab Grid:** Type fret numbers directly over standard 6-string guitar notation (`E A D G B e`).
- **Keyboard Navigation:** Navigate seamlessly between strings, columns, and staves using arrow keys.
- **Barline Support:** Easily insert barlines (`|`) to structure measures and end bars.
- **Pixel-Perfect PDF Export:** Export cleanly formatted multi-page PDFs using `html2pdf.js` with zero margin drift or cutoffs.
- **Zero Setup:** Runs completely in the browser with no build step, dependencies, or backend required.

---

## 🚀 Getting Started

1. **Clone the repository:**
   git clone [https://github.com/your-username/guitar-tab-editor.git](https://github.com/your-username/guitar-tab-editor.git)

2. **Open the app:**
   Simply double-click `index.html` or open it in any modern web browser.

---

## ⌨️ How to Use

| Action | Control |
| :--- | :--- |
| **Navigate Grid** | Arrow Keys (`Up`, `Down`, `Left`, `Right`) |
| **Enter Fret** | Type numbers (`0`–`24`) on any string |
| **Add Barline** | Press `|` or click the **Insert Barline** button |
| **Export File** | Click **Export PDF** to save a printable 2-page document |

---

## 🛠️ Built With

* Plain HTML5 / CSS3 (Flexbox & CSS Grid)
* Vanilla JavaScript (DOM manipulation & event handling)
* [html2pdf.js](https://github.com/eKoopmans/html2pdf.js) — Client-side HTML to PDF rendering

---

## 📜 License

This project is open-source and available under the [MIT License](LICENSE).