# Assignment 3.4 — Semantic HTML & Accessibility

## Theory

The objective of this assignment is to convert a webpage built using generic `<div>` elements into a semantically structured HTML page. Semantic HTML uses meaningful tags to describe the purpose of different parts of a webpage, making it easier to understand, maintain, and navigate.

### 1. Semantic HTML Elements

Semantic HTML elements clearly describe the role of the content they contain.

- `<header>`: Defines the introductory area of a webpage or section, usually containing a title, logo, or introductory content.
- `<nav>`: Contains navigation links used to move between pages or sections.
- `<main>`: Represents the primary content of the webpage.
- `<section>`: Groups related content under a common theme, usually with a heading.
- `<article>`: Represents independent, self-contained content, such as a blog post or news article.
- `<aside>`: Contains supplementary information related to the main content, such as related links or a sidebar.
- `<footer>`: Defines the footer of a webpage or section, often containing copyright information or contact details.

### 2. Replacing Div-Based Structure

The `<div>` element is a generic container without any specific semantic meaning. In this assignment, appropriate `<div>` elements are replaced with semantic elements wherever possible.

This improves the organization of the webpage and makes the HTML code more meaningful and easier for developers to understand.

### 3. Navigation and Main Content

Navigation links are placed inside the `<nav>` element so users and assistive technologies can identify the navigation area easily.

The primary content of the webpage is placed inside the `<main>` element. A page should generally have only one visible main content area.

### 4. Correct Heading Hierarchy

HTML headings range from `<h1>` to `<h6>`. They organize content according to its importance and structure.

- `<h1>`: Represents the main heading of the page.
- `<h2>`: Represents major sections.
- `<h3>`: Represents subsections within a section.

Headings should follow a logical hierarchy to make the content easier to read and navigate. They should not be selected only for their visual size.

### 5. Adding Meaningful Alt Text

The `alt` attribute provides a text alternative for images. It helps screen-reader users understand the purpose or content of an image and provides alternative text when an image cannot be displayed.

Alt text should be concise and descriptive. Decorative images that do not convey meaningful information should generally use an empty `alt` attribute (`alt=""`).

### 6. Improving Accessibility

Accessibility ensures that a webpage can be used by people with different abilities, including those who rely on screen readers or keyboard navigation.

In this assignment, accessibility is improved by:

- Using semantic HTML elements appropriately.
- Keeping navigation links inside `<nav>`.
- Organizing content with meaningful headings.
- Adding suitable alternative text to images.
- Using descriptive link text.
- Ensuring that page sections are clearly structured and understandable.

### 7. Before-and-After Comparison


## before
![alt text](<before 1st screenshot.png>)
![alt text](<before second screenshot.png>)
 ## AFTER
![alt text](<after 1st screenshot.png>)
![alt text](<after 2nd screenshot.png>)
## Conclusion

In this assignment, I learned how to convert a div-based webpage into a semantic HTML structure using `<header>`, `<nav>`, `<main>`, `<section>`, `<article>`, `<aside>`, and `<footer>`. I also learned the importance of a logical heading hierarchy, meaningful image alt text, and descriptive navigation links. These practices improve code readability, maintainability, and web accessibility.