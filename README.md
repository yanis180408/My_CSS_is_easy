# Welcome to My CSS Is Easy
***

## Task
The goal of this project is to style a web page using only CSS.
The HTML structure is written first, then CSS rules are used to control the layout, colors, typography and spacing, without any JavaScript.
The challenge lies in understanding how selectors, the box model and the cascade work together, and in building a clean layout that looks right on different screen sizes.

## Description
I solved this problem by writing semantic HTML first and then styling it in a separate stylesheet:
- **Structure** : the page uses semantic tags (`header`, `nav`, `main`, `section`, `footer`) so the content stays readable even without styles.
- **Selectors** : the styles rely on element, class and id selectors, with pseudo-classes such as `:hover` and `:nth-child` for interactive and repeated elements.
- **Box Model** : margins, padding and borders are set consistently, with `box-sizing: border-box` applied to every element.
- **Layout** : the main layout is built with Flexbox, and CSS Grid is used where a grid of items is needed.
- **Typography and Colors** : fonts, sizes and a small color palette are defined in one place using CSS variables, so the theme is easy to change.
- **Responsive Design** : media queries adapt the layout for tablets and phones.
- **Organization** : the CSS is split into clear sections (reset, layout, components, responsive) and commented.

## Installation
The project runs entirely in the browser, so no compilation is needed.
1. Get the project :
```bash
git clone [REPOSITORY_URL]
cd my_css_is_easy
```

2. Open the page directly in a browser :
```bash
open index.html
```

3. Or serve it locally (optional) :
```bash
python3 -m http.server 8000
```
Then visit `http://localhost:8000` in your browser.

## Usage
Open `index.html` in a browser. Resize the window or use the browser's developer tools (`F12`, then the device toolbar) to see the responsive layout, and hover over the interactive elements to see the `:hover` effects.

**Project structure :**
```
my_css_is_easy/
├── index.html
├── css/
│   └── style.css
└── images/
```

### The Core Team


<span><i>Made at <a href='https://qwasar.io'>Qwasar SV -- Software Engineering School</a></i></span>
<span><img alt='Qwasar SV -- Software Engineering School's Logo' src='https://storage.googleapis.com/qwasar-public/qwasar-logo_50x50.png' width='20px' /></span>
