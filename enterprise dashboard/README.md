# Enterprise Dashboard Foundation

This project provides the structural foundation for an enterprise dashboard, designed with a strong emphasis on semantic HTML5 standards and Web Content Accessibility Guidelines (WCAG) 2.1.

## Objective
To build an accessible multi-page layout including a navigation header, sidebar, main content area, data tables, and modal dialogs.

## Features
- **Semantic HTML5:** Proper use of `<header>`, `<nav>`, `<main>`, `<section>`, `<article>`, `<aside>`, and `<footer>` elements to ensure a logical document outline.
- **Accessibility (a11y):** 
  - Implementation of `aria-labels` and `aria-describedby` where appropriate.
  - Skip links for keyboard navigation.
  - Accessible form controls with properly linked `<label>` tags and `fieldset`/`legend` groupings.
  - Data tables with explicit `scope` attributes for row and column headers.
  - Interactive `<dialog>` component for native accessible modals.
- **Component Architecture:** Key structural elements are isolated in the `components/` directory to demonstrate modular design capabilities.

## Validation
The HTML has been written to strictly adhere to standard specifications and passes the W3C HTML validator with zero syntax errors.

## Folder Structure
- `index.html`: The main structural layout integrating all elements.
- `components/`: Contains isolated structural representations of individual dashboard UI elements.

