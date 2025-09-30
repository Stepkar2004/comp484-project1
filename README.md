Link to website: [link]

# Project 1: HTML & CSS

This project is a small informational website about Quantum Mechanics.

## Unique Elements & Attributes Used

As per the project requirements, the following unique elements and attributes have been implemented:

### Elements

1.  **`<small>`**
    *   **Where:** Used in the footer of every page and for notes (e.g., in `glossary.html`).
    *   **Why:** To represent side-comments, fine print, and copyright information, which is the semantic purpose of the tag.

2.  **`<iframe>`**
    *   **Where:** Used on the `experiments.html` page.
    *   **Why:** To embed an external YouTube video directly into the page, providing a visual explanation of the double-slit experiment.

3.  **`<ins>`**
    *   **Where:** Used in the footer of every page and within the text on some pages (e.g., `index.html`).
    *   **Why:** To highlight text that is considered an "insertion" or a key idea, making it stand out semantically.

### Attributes

1.  **`tabindex`**
    *   **Where:** Applied to all links in the main navigation menu in the header of each page.
    *   **Why:** To create a clear and logical keyboard navigation order (1 through 6), improving accessibility for users who do not use a mouse.

2.  **`longdesc`**
    *   **Where:** Applied to all main images on pages like `index.html`, `history.html`, etc.
    *   **Why:** To provide a programmatic link to a section on the same page that contains a detailed description of the image. This is an accessibility feature for users with screen readers who need more context than a short `alt` text can provide.

3.  **`translate`**
    *   **Where:** Used on the main `<h1>` title on every page and on a specific symbol in `glossary.html`.
    *   **Why:** The `translate="no"` attribute is used to tell browser translation services not to translate the site's proper name ("Quantum Mechanics Mini-Guide") or specific scientific symbols, preserving their original form.
