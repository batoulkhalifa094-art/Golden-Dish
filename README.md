# Golden Dish

A luxury restaurant website built with **HTML5** and **CSS3 only** (no JavaScript, no frameworks) as a hands-on practice project for learning front-end fundamentals.

**Live demo:**  https://batoulkhalifa094-art.github.io/Golden-Dish/

## About the project

Golden Dish is a static, single-page restaurant website. The goal was to build a complete, good-looking page from scratch: structuring the content with semantic HTML and bringing it to life with modern CSS layouts, transforms, transitions, and animations.

## Page sections

- **Offers bar**: delivery, fresh ingredients, and 24/7 support highlights
- **Header**: logo, search bar, social icons, and a navigation bar with animated hover borders
- **Hero**: full-screen banner with the restaurant slogan
- **Services**: three circular cards (fresh ingredients, vegetarian, healthy meals) with a hover overlay
- **Special dishes**: offer cards with old and new prices and an animated pointing hand on hover
- **Main courses** and **Starters and desserts**: image showcase sections with scroll-triggered animations
- **Our Luxury Menu**: four 3D flip cards. The front shows an image, category tag, and rating stars; the back lists the dish options
- **Footer**: logo and social links

## CSS techniques used

| Technique | Where it is used |
| --- | --- |
| Flexbox | Header, offers bar, menu cards, special dishes, footer |
| CSS Grid | Showcase sections and image layouts |
| Positioning and pseudo-elements (`::before`, `::after`) | Gradient overlays on cards, animated nav borders, decorative diamond divider |
| `transform` | Hover scaling, rotation, and the 3D card flip |
| `transition` | Smooth hover effects on buttons, cards, and links |
| `@keyframes` animations | Pointing hand animation and entrance effects |
| Scroll-driven animations (`animation-timeline`) | Service circles and showcase images animate as they enter the viewport |
| 3D transforms (`perspective`, `transform-style: preserve-3d`, `backface-visibility`) | Menu flip cards |
| `scroll-behavior: smooth` | Smooth navigation between sections |
| Gradients and `box-shadow` | Card overlays and glowing hover effects |

## Technologies

- HTML5 (semantic structure)
- CSS3
- [Font Awesome 6](https://fontawesome.com/) for icons

## Browser support

The scroll-driven animations (`animation-timeline`) are supported in recent versions of Chrome and Edge. In browsers without support, the elements simply appear without the scroll effect. For the best experience, use the latest Chrome or Edge.

## Project structure

```
Golden-Dish/
├── index.html
├── style/
│   └── style.css
└── images/
```

## How to run

1. Clone the repository:
   ```
   git clone https://github.com/YOUR-USERNAME/Golden-Dish.git
   ```
2. Open `index.html` in your browser.

No installation or build tools are needed.

## What I practiced

- Building a full page layout with Flexbox and Grid
- Absolute and relative positioning to layer elements
- Creating overlays and gradients with pseudo-elements
- Making a 3D flip card with CSS transforms only
- Writing reusable `@keyframes` animations and smooth transitions
- Animating elements on scroll with CSS only
- Organizing a project into HTML, CSS, and images folders

## Author

**Batoul Wafik Khalifa**
Software engineering student
