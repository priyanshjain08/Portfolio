# Priyansh Jain --- Personal Portfolio

A responsive, single-page personal portfolio website for **Priyansh
Jain**, a first-year BCA student at Dezyne École Collège, Ajmer. The
site introduces the portfolio owner, presents web-development skills and
coursework assignments, and provides contact options


## Features

-   **Single-page layout** with Home, About, Skills, Assignments, and
    Contact sections.
-   **Responsive design** with layouts that adapt to desktop, tablet,
    and mobile screen sizes.
-   **Animated hero section** with an introductory profile,
    call-to-action links, and skill labels.
-   **About section** with an education overview and learning-path
    timeline.
-   **Skills section** with visual proficiency meters for HTML5, CSS3,
    JavaScript, responsive design, Flexbox/Grid, and Git/GitHub.
-   **Assignment cards** describing six HTML and CSS coursework topics.
-   **Contact section** with contact links and a message form.
-   **Motion and interaction details**, including hover transitions,
    animated elements, and a scrolling skills ticker.
-   **Reduced-motion support** through `prefers-reduced-motion`.

## Built With

-   **HTML5** --- page structure and semantic content.
-   **CSS3** --- styling, responsive layouts, animations, and visual
    effects.
-   **Google Fonts** --- Bricolage Grotesque and Figtree.
-   **Font Awesome 6.4.0** --- interface and social icons.
-   **Unsplash** --- remote photography used in the page.

There is no build system, package manager, or JavaScript framework
required by the supplied HTML file.

<!--## Getting Started

### Run locally

1.  Download or clone this repository.
2.  Make sure the portfolio HTML file is named `index.html` (or open the
    supplied HTML file directly).
3.  Open `index.html` in a modern web browser.

You can also run a simple local server from the project directory:

``` bash
python -m http.server 8000
```

Then visit <http://localhost:8000> in your browser.-->

## Project Structure

``` text
.
└── index.html    
└── style.css
```


<!--## Customization

Before publishing, review the HTML and replace the sample or placeholder
content with your own:

1.  **Profile and education:** Update the page title, meta description,
    name, course details, college information, and learning path.
2.  **Images:** Replace the Unsplash image URLs with your own images if
    desired. Keep useful `alt` text for accessibility.
3.  **Skills:** Edit the skill names, descriptions, and `--w` percentage
    values used by the progress bars.
4.  **Assignments:** Change the six assignment cards to match your
    actual projects and coursework.
5.  **Contact details:** Update the phone, WhatsApp, email, and location
    links and visible text.
6.  **Social profiles:** Replace the generic GitHub and LinkedIn
    destinations with your own profile URLs.
7.  **Colors and typography:** Adjust the CSS custom properties in
    `:root` to change the color palette and font choices.-->

## Contact Form Note

The current form uses a `mailto:` action. Submitting it attempts to open
the visitor's default email application with the form fields prepared;
it does **not** send the message through a website backend. Configure
the form's recipient address before publishing. For a form that works
without relying on the visitor's email application, connect a
form-handling service or implement a backend.

## External Resources

The page loads Google Fonts, Font Awesome, and Unsplash images from
external services. An internet connection is therefore needed for those
resources to load. The core page structure and embedded CSS are local.

## Accessibility and Responsive Behavior

The markup includes section navigation, descriptive image alternative
text, visible keyboard-focus styling, and a reduced-motion media query.
Test the page with keyboard navigation and at multiple viewport sizes
before deployment.

<!--## Deployment

This is a static website and can be hosted on any static web host.
Upload the HTML file (named `index.html` for the usual default entry
point) and ensure the external resource URLs and personal links are
correct.-->

------------------------------------------------------------------------

*Personal portfolio project --- BCA First Year, HTML5 and CSS3
assignment.*
