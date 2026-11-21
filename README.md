# Sweet Crumbs — Home Bakery Website

A responsive showcase website for a boutique home bakery featuring menu browsing, order inquiries, and serverless form processing via Google Apps Script and Google Sheets.

Live Demo: [https://krissp-momo.github.io/home-bakery-project/](https://krissp-momo.github.io/home-bakery-project/)

---

## Highlights

- **Product Catalog:** Interactive menu display with item imagery, descriptions, and dietary tags (eggless, customized options).
- **Asynchronous Inquiries:** Contact and pre-order inquiry submissions handled via JavaScript `FormData` and `fetch` directly to a Google Apps Script web endpoint without page reloads.
- **Automated Data Capture:** Form submissions are appended in real-time to a connected Google Sheet for order tracking and inventory management.
- **Responsive Layout:** Mobile-first layout using semantic HTML5 and vanilla CSS Flexbox and Grid.

---

## Tech Stack

- **Frontend:** Semantic HTML5, CSS3, Vanilla JavaScript (ES6+)
- **Backend / Integration:** Google Apps Script (Web App Endpoint), Google Sheets (Data Store)
- **Deployment:** GitHub Pages

---

## Architecture Flow

```text
Visitor Submits Form (index.html)
        │
        ▼  FormData (fetch POST)
Google Apps Script Web App (doPost handler)
        │
        ▼  Append Row
Google Sheets Order Tracker
```

---

## Local Setup

1. Clone repository:
   ```bash
   git clone https://github.com/krissp-momo/home-bakery-project.git
   cd home-bakery-project
   ```
2. Open `index.html` in your web browser.

---

## Author

- Krishna Patel — [GitHub](https://github.com/krissp-momo) | [LinkedIn](https://www.linkedin.com/in/krishna-patel-a15b1a319/)
