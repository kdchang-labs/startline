# Life Starting Point Index

> How many of these did you have before you turned 18? Check the ones that apply and see where your starting line was.

**Live Demo:** https://labs.kdchang.com/startline

---

## About

The Life Starting Point Index is a lightweight interactive quiz that measures the resources and opportunities you had growing up, across 20 questions in three categories:

| Category | Questions | Description |
|----------|-----------|-------------|
| Personal Resources & Education | 8 | Private space, devices, extracurricular training, talents, etc. |
| Family Background & Assets | 5 | Family education level, financial planning, location, etc. |
| Global Exposure & Opportunities | 7 | Overseas travel, international education, dual citizenship, etc. |

After completing the quiz, you'll receive a Level 0–5 rating along with a breakdown score for each category.

---

## Features

- Live scoring: Sticky Score Bar updates in real time as you check items
- Result modal: Animated display of score, level, and three-category breakdown
- Share: One-click copy result text / share to X (Twitter)
- Zero dependencies: Pure HTML + CSS + Vanilla JS
- Responsive: Works on both mobile and desktop

---

## Getting Started

```bash
# Clone the repo
git clone git@github.com:kdchang-labs/startline.git
cd startline

# Start a local dev server
npx serve .

# or

python3 -m http.server 8080
```

Open your browser at `http://localhost:8080`

---

## Project Structure

```
├── index.html        # Main page (all CSS / JS included)
├── images/
│   └── favicon.ico
└── CNAME             # GitHub Pages custom domain
```

---

## Level Reference

| Score | Level | Label |
|-------|-------|-------|
| 0–3 | LEVEL 0 🌱 | Humble Origins |
| 4–7 | LEVEL 1 🏡 | Working Class |
| 8–11 | LEVEL 2 🏙️ | Middle Class |
| 12–14 | LEVEL 3 💼 | Well-off |
| 15–17 | LEVEL 4 🌏 | High Resources |
| 18–20 | LEVEL 5 👑 | Top Tier |

---

## Credits

Inspired by: [台灣特權指數 @swe_roger on Threads](https://www.threads.com/@swe_roger/post/DS1kWzLE-7F/)

---

## License

MIT
