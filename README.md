# Responsive Navbar (CSS Task 10.2)

A simple navigation bar built with **HTML** and **CSS**, using Flexbox for the layout.

## Features

- Logo on the left
- Navigation links (Home, About, Contact) in the center
- Orange Login button on the right
- Dark background navbar
- Clean layout using Flexbox

## Technologies Used

- HTML5
- CSS3 (Flexbox)

## Project Structure

```
Task10/
├── index.html   # Navbar structure
├── style.css    # Navbar styling
└── README.md
```

## CSS Concepts Used

- `*` selector with `margin: 0`, `padding: 0`, `box-sizing: border-box` (CSS reset)
- `display: flex` to arrange items in a row
- `justify-content: space-between` to spread logo, links, and button
- `align-items: center` to align items vertically
- `list-style: none` and `text-decoration: none` to clean up the links
- `gap` to add space between links
- Class selectors: `.navbar`, `.logo`, `.navlink`, `.btn`

## How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/shanmugashobana/CSS-Task-10.2.git
   ```
2. Open the project folder.
3. Open `index.html` in any browser (or use **Live Server** in VS Code).

## Future Improvements

- Add hover effects on links and button
- Make the navbar responsive for mobile (hamburger menu)
- Add page content below the navbar
