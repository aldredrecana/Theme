https://roadmap.sh/projects/theme-switcher

# Theme

Theme Switcher with CSS Variables

A JavaScript-free theme switcher built for the roadmap.sh Theme Switcher project. Three radio inputs control a shared token layer of CSS custom properties, which a single preview card reads from — switching themes never touches the HTML or duplicates the card.

Live Demo

Add your deployed link here once hosted (see Deployment below).

Features
Three themes: Light, Dark, and Sunset, switchable with no JavaScript
A single design-token layer (--color-bg, --color-surface, --color-text, --color-muted, --color-accent, --color-border, --radius-md) defined once at :root and fully overridden per theme
Theme switching implemented with the :has() selector reacting to :checked radio state
Active theme option highlighted using the general sibling combinator (:checked + label)
Fully keyboard accessible — real <input type="radio"> elements, visually hidden but never removed from the accessibility tree, with visible :focus-visible outlines
Tech Stack
HTML5
CSS3 (custom properties, :has(), sibling selectors, :focus-visible)
No JavaScript
