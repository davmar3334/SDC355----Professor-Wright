# Dave Martinez - Portfolio

Personal portfolio page implementing control flow and DOM manipulation for the Creating and Referencing DOM Elements project.

## Features
- **Dynamic DOM element**: A new paragraph is created and appended to the About section using `createElement()` and `appendChild()`.
- **Selector-based modifications**: Two existing elements (About and Contact headings) are selected and updated (style and content).
- **Timed form confirmation**: On submit, `preventDefault()` is used, a “Sending message...” status appears, then after 2.5 seconds a success message is shown via `setTimeout()`.
- **Featured Content** with conditional logic
- **Skills list** generated with a `for` loop
- **Dark Mode** toggle
- Delayed welcome notification

## How to use
1. Upload `index.html` to a GitHub repository.
2. Enable GitHub Pages (Settings → Pages → Source: main branch / root).
3. Open the live site link.

Change the `projectCount` variable in the script (currently set to `2`) to test both conditional branches.
