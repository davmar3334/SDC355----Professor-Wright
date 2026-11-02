# Dave Martinez - Persistent Storage – Modal, Tooltip & Dark Mode

**Release:** v1.0  
**Date:** 2026-11-02  
**Language:** HTML, CSS, JavaScript

### Overview
This release adds persistent storage and improved user experience features to the project page.  
User preferences and interactions are now remembered across page loads.

### What was added
- **Welcome modal** that appears on page load with the message “This page is a work in progress” and a Close button
- **Tooltip** on the Contact Form Submit button (“Click to send your message!”)
- **Dark Mode persistence** using `localStorage` so the user’s preference is saved and automatically applied on future visits
- Toggle state (checkbox) reflects the stored dark mode preference

### Files
- `index.html` – Updated page containing the modal, tooltip, and dark mode logic
- (Any supporting CSS/JS files if separated)

### How to test
1. Open the page in a browser
2. Close the welcome modal
3. Hover over the Submit button to see the tooltip
4. Toggle Dark Mode, then refresh the page — the mode should stay active
5. Check `localStorage` in Developer Tools → Application tab to confirm the preference is stored

---
