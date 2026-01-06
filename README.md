# Four Card Feature Section

This is a solution to the **Four Card Feature Section** challenge on Frontend Mentor.  
The goal of this challenge is to build a responsive layout using modern CSS techniques.

---

## 🚀 Overview

### The challenge

Users should be able to:

- View the optimal layout depending on their device’s screen size
- See a clean, centered four-card layout on desktop
- See cards stacked vertically on mobile

---

## 🛠️ Built with

- Semantic HTML5
- CSS Grid
- Flexbox
- CSS Custom Properties (Variables)
- Google Fonts (Poppins)
- Mobile-first workflow

---

## 📂 Project structure

├── index.html
├── styles.css
├── images/
│ ├── icon-supervisor.svg
│ ├── icon-team-builder.svg
│ ├── icon-karma.svg
│ └── icon-calculator.svg
└── README.md

yaml
Copy code

---

## 🎨 Design choices

- **CSS Grid** is used for the card layout to easily span cards across rows
- **Flexbox** is used inside cards for vertical alignment
- **CSS variables** are used for colors to keep the design consistent and maintainable
- Cards automatically size based on their content
- Shadows are applied using layered `box-shadow` for depth

---

## 📱 Responsive behavior

- Desktop: 3-column grid with center-aligned side cards
- Mobile (`≤ 375px`): Single-column stacked layout
- Grid positioning is reset using `revert` inside media queries

---

## 🧠 What I learned

- How `grid-row` and `grid-column` work with spanning
- How to prevent flex and grid items from stretching unexpectedly
- Using `aspect-ratio` and intrinsic sizing concepts
- Structuring CSS for scalability and readability

---

## 🔗 Links

- Live Site URL: https://chetanchaudhari.github.io/four-card-feature-section/
- **Challenge**: https://www.frontendmentor.io/challenges/four-card-feature-section-weK1eFYK
- **Frontend Mentor**: https://www.frontendmentor.io

---

## ✍️ Author

- Frontend Mentor – [Your profile link]
- GitHub – [Your GitHub link]

---

## 🙌 Acknowledgements

Thanks to Frontend Mentor for providing great real-world frontend challenges.
