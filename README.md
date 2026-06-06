Simple Omelette Recipe Page
A clean, responsive recipe card webpage displaying a simple omelette recipe with ingredients, step-by-step instructions, and nutritional information.

Project Structure
├── index.html       # Main HTML file
├── page.css         # Stylesheet
└── image-omelette.jpeg  # Omelette image (required)

Features

Recipe overview — title, description, and preparation time breakdown
Ingredients list — with optional filling suggestions
Step-by-step instructions — numbered cooking steps
Nutrition table — calories, carbs, protein, and fat per serving
Responsive design — adapts to mobile screens (375px and below)


Usage

Clone or download the project files.
Place your omelette image in the same directory and name it image-omelette.jpeg.
Open index.html in any modern web browser — no build tools or dependencies required.


Responsive Behavior
Screen SizeLayoutDesktop (default)Centered card, 610px wide, left-offset with margin-left: 500pxMobile (≤ 375px)Full-width card, zero margins, reduced font sizes

Note: The desktop layout uses a fixed margin-left: 500px on .box. For better centering across various screen sizes, consider replacing this with margin: 0 auto and wrapping the body with display: flex; justify-content: center.


Styling Overview

Font: Young Serif (display), Sans-serif (preparation section)
Primary accent color: rgb(167, 47, 67) — used for headings and bold values
Background: rgb(248, 225, 229) (page), white (card), rgb(247, 229, 229) (prep section)
Dividers: Thin 0.5px black horizontal rules between sections


Known Issues / Suggestions

margin-left: 500px on .box may cause layout issues on screens narrower than ~1100px. Replace with margin: 0 auto for more robust centering.
Several <li> elements are nested incorrectly inside other <li> tags in the HTML — they should be sibling items within the same <ul> or <ol>.
The font young serif should be imported via Google Fonts or another provider, otherwise it will fall back to the browser default.


License
This project is for educational/personal use.
