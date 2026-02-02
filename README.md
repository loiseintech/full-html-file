# Assignment: Build a Complete Semantic Website

**Program:** Full Stack Web Development  
**Institution:** NextGen Coding Hub  
**Level:** Beginner  
**Submission Type:** Individual  
**Submission Method:** GitHub Repository (Private)

---

##  Assignment Objective

The goal of this assignment is to build a **fully structured, semantic, and branded HTML webpage** that demonstrates your understanding of:

- Proper HTML document structure
- Semantic HTML elements
- Headings, paragraphs, lists, and tables
- Images, logos, and favicons
- Accessibility using `alt` text
- Basic CSS styling
- Git and GitHub workflow

This assignment simulates building a **real, professional webpage**

---

## Required Project Structure

Your project **must follow exactly** the structure below:

project-folder/
│── index.html
│── styles.css
│── README.md
│── images/
│ ├── logo.png
│ ├── favicon.ico
│ ├── hero.jpg
│ └── gallery1.jpg

Stick to the structure above

---

## Part 1: HTML Document Setup (MANDATORY)

Your `index.html` file **must include**:

- `<!DOCTYPE html>`
- `<html lang="en">`
- `<head>` section with:
  - `<meta charset="UTF-8">`
  - `<meta name="viewport">`
  - `<title>`
  - `<link rel="icon">` (favicon)
  - `<link rel="stylesheet">`
- `<body>` section

---

## Part 2: Semantic Page Layout

Your webpage must use **semantic HTML elements** correctly.

### Required Semantic Elements
You **must include all** of the following:

- `<header>`
- `<nav>`
- `<main>` (only one per page)
- `<section>` (at least 3)
- `<article>` (at least 3)
- `<aside>`
- `<footer>`

---

## Part 3: Header & Navigation

Inside the `<header>`:

- A **logo image**
- A main heading (`<h1>`)
- A navigation menu using `<nav>` with:
  - At least **3 links**
  - A list (`<ul>` and `<li>`)

Each navigation link should point to a section using `id` attributes.

---

## Part 4: Main Content Requirements

### Section 1: About
- `<section>` with an `id`
- `<h2>` heading
- At least **two paragraphs**
- One image with proper `alt` text

---

### Section 2: Programs
- `<section>` with an `id`
- Two `<article>` elements
- Each article must include:
  - `<h3>`
  - Paragraph
  - A **nested list** (ordered list inside unordered list or vice versa)

---

## Part 5: HTML Table

Include **one table** with:

- `<table>`
- `<thead>`
- `<tbody>`
- At least **4 columns**
- At least **5 rows**
- Meaningful headings using `<th>`

Example topics you can explore:
- Weekly schedule
- Course timetable
- Program overview

---

## Part 6: Images & Accessibility

Your page must include:

- A **logo**
- A **hero image**
- At least **one additional image**

### Image Rules
✔ All images must:
- Be stored inside the `images/` folder
- Use **relative paths**
- Include descriptive `alt` text


---

## Part 7: Favicon (REQUIRED)

- Add a favicon using `<link rel="icon">`
- The favicon must:
  - Be placed inside the `images/` folder
  - Appear in the browser tab

---

## Part 8: CSS Styling

Create a `styles.css` file and apply styling for:

### Required Styling Areas
- Headings (`h1`, `h2`, `h3`)
- Logo size and alignment
- Images:
  - Rounded corners (`border-radius`)
  - Spacing (`margin`)
- Table:
  - Borders
  - Cell padding
- Page spacing using `margin` and `padding`

### CSS Properties You Must Use
margin
padding
border-radius
width or max-width

### Inline CSS is NOT allowed.

---

## Part 9: Git & GitHub Workflow

You must:

1. Initialize Git in your project
2. Make **at least 3 commits**, for example:
   - Initial HTML structure
   - Content added (sections, tables, lists)
   - Styling, images, and branding
3. Push the project to a **public GitHub repository**

### Example Commit Messages
```bash
git commit -m "Initial semantic HTML structure"
git commit -m "Added content, tables, and lists"
git commit -m "Added images, favicon, and CSS styling"

### ==== Submission Instructions ====

Submit:

A link to your public GitHub repository

Ensure:

The page loads correctly in a browser

All files are pushed to GitHub

The repository includes this README.md

| Area                    | Marks   |
| ----------------------- | ------- |
| Semantic HTML Structure | 20      |
| Content Organization    | 15      |
| Images & Accessibility  | 15      |
| Tables & Lists          | 15      |
| CSS Styling             | 20      |
| Git Usage               | 10      |
| **Total**               | **100** |

=== Common Mistakes to Avoid

Missing favicon

Images outside images/ folder

No alt text

Using only <div> instead of semantic tags

No Git commits

Inline CSS

Final NOTE

This assignment represents your first professional-style webpage.

Focus on:

Clean structure

Correct semantics

Readable code

Proper file organization

Well-structured code is more important than fancy design.

Good luck Loise!

--------Jerry Tarus -------

NextGen Coding Hub# semantic-html-project
