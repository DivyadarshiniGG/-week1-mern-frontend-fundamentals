# Week 1 — Frontend Fundamentals (HTML, CSS, React Basics)

**Full Stack Web Development (MERN) Course**
**Submitted by:** Divya Darshini G G
**GitHub:** [DivyadarshiniGG](https://github.com/DivyadarshiniGG)
**LinkedIn:** [divyadarshini793](https://www.linkedin.com/in/divyadarshini793/)

## Topics Covered
- HTML5 semantic structure
- CSS3 (Flexbox, Grid, Responsive Design)
- JavaScript ES6+ fundamentals
- React.js basics (Components, Props, State, Events)

## What's in this repo

### 1. `portfolio/`
A responsive personal portfolio site built with plain HTML5 and CSS3 — no frameworks.

- **Sections:** About, Education, Skills, Projects, Experience & Recognition, Contact
- **Techniques used:** semantic HTML5 tags, CSS Flexbox and Grid, media queries for responsiveness, CSS custom properties for theming
- **To view:** open `portfolio/index.html` in any browser

### 2. `react-components/`
Five reusable React components, demonstrating props, state, and dynamic rendering.

| Component | Demonstrates |
|---|---|
| `Header` | Props (title, nav links) |
| `Footer` | Props (year, owner) |
| `Card` | Props, rendered dynamically from an array with `.map()` |
| `Button` | Props (variant, click handler), reused across the page |
| `ContactForm` | Local state, controlled inputs, form submission |

- Runs directly in the browser via React + Babel CDN (no build step needed) — requires an internet connection to load the React/Babel scripts.
- **To view:** open `react-components/index.html` in any browser

### 3. `react-blog-ui/`
Mini project: a React blog layout that renders post cards from a JSON data source, with live search and category filtering.

- **Data source:** `posts.json` (also embedded as a fallback directly in the script, so the page works even when opened directly as a file, with no server required)
- **Features:** search by keyword, filter by category, empty-state message when no results match
- **To view:** open `react-blog-ui/index.html` in any browser

## Learning Outcome
Understanding of frontend design principles, responsive layout creation, and React component structure — building components that take props, manage their own state, and render dynamically from data.
