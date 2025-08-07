# ChronoView: A Timeline Application

This repository contains the source code for ChronoView, a simple and elegant web-based timeline application.

<img width="994" height="896" alt="image" src="https://github.com/user-attachments/assets/117fa478-7403-4fcc-a917-bd23c989a94e" />


## Stage 1: Static HTML Skeleton

This initial commit establishes the foundational HTML structure of the application. The focus is purely on creating a semantic and accessible document that serves as a solid base for future development. No styling (CSS) or interactivity (JavaScript) is included at this stage.

### Project Files

- **`index.html`**: The single entry point for the application.

### Key Structural Components

The `index.html` file is organized using semantic HTML5 tags to ensure clarity and accessibility:

* **`<header>`**: Contains the application's logo placeholder and a button for the future theme toggle feature.
* **`<main>`**: Acts as the primary container for the core content of the page.
* **`<nav>`**: A dedicated navigation block, currently serving as a placeholder for filtering and sorting controls.
* **`<section id="timeline">`**: The main section where all timeline events will be rendered. It contains a sample `<article>` to demonstrate the intended structure.
* **`<article>`**: Represents a single event on the timeline. Each article is structured with its own `<header>`, `<p>` tags for descriptions, and a `<figure>` for associated images.
* **`<div id="modal">`**: An empty container that will be used by JavaScript to display detailed information in a pop-up window.

### How to View

To see the current structure, simply open the `index.html` file in any web browser.

### Next Steps

The next stage will focus on applying CSS to style the layout, typography, and visual components of the timeline.
