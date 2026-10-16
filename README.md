# Playing Cards 🃏

A visually precise recreation of standard playing cards built entirely with pure HTML and CSS. This project focuses on advanced CSS positioning, utilizing nested Flexbox layouts and CSS transforms to mimic the authentic look and feel of real playing cards without using any external images.

## ✨ Features

- **Pure CSS & HTML Design:** Built without a single image file. All card suits (♠, ♣, ♥) are rendered using standard Unicode characters, keeping the project extremely lightweight.
- **Advanced Flexbox Layout:** Uses heavily nested Flexbox containers (`align-self`, `justify-content: space-evenly`, `flex-direction: column`) to perfectly position the corner indices and center suit symbols.
- **Authentic Orientation:** Employs CSS `transform: rotate(180deg)` on the bottom-right corners and the bottom center suits to accurately replicate the upside-down design of real playing cards.
- **Responsive Wrapper:** Cards flow naturally to the next row on smaller screens using `flex-wrap: wrap`.

## 🚀 Demo

[Live Demo](https://mehmetereneksi.github.io/Page-of-Playing-Cards/)

## 🛠️ Technologies Used

- **HTML5:** Semantic structuring and Unicode typography.
- **CSS3:** Flexbox, CSS Transforms (`rotate`), Box Shadows, and custom styling.

## 📁 Project Structure

```text
├── index.html    # Main document containing the structure and Unicode suits of the cards
└── styles.css    # Stylesheet for card dimensions, Flexbox layouts, and rotational transforms
```
