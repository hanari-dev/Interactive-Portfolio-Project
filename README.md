# Interactive-Portfolio-Project
Interactive web portfolio project showcasing DOM events, array filtering, and responsive design techniques.

## Live Demo 
[View Portfolio on GitHub Pages](https://hanari-dev.github.io/Interactive-Portfolio-Project/)

## Preview
**Main Portfolio View** `![Main Portfolio View](hub.png)`
**Filtered Projects** `![Project Filtering in Action](filter.png)`

## Technical Highlights 
- **DOM Manipulation:** Dynamically rendering project cards using JavaScript template literals.
- **Event-Driven Programming:** Using `input`, `keydown`, and `click` events to create a responsive user interface.
- **Data Filtering:** Implemented a filtering pipeline that sorts projects by technology and search keywords without reloading the page.
- **Event Delegation:** Optimized performance by using a single listener on the parent grid for all project card interactions.
- **Responsive Design:** CSS-driven grid layout that adapts to different screen sizes.

## How It Works
- **Data Structure:** Projects are stored as an array of objects, making it easy to scale the portfolio.
- **Filter Logic:** Users can click technology badges (HTML, CSS, JavaScript) to see specific projects, or use the live search bar to find projects by title or description.
- **Real-time Updates:** The project grid re-renders instantly on every keystroke or filter selection.

## Technologies Used
- **HTML5:** Semantic markup for structure.
- **CSS3:** Flexbox and Grid for responsive styling.
- **JavaScript:** ES6+ syntax, `Array.filter()`, `map()`, and DOM event handling.
