# CSY1063-AS1-GetSauced-Web-Development-Project
web development project
# GetSauced Portfolio Website – CSY1063 AS1 Build Brief

## Project Overview
Create a responsive multi-page website for my CSY1063 Assignment 1 submission.

The website should be designed around my brand **GetSauced**, which is a luxury-inspired showcase of premium watches and sneakers. The final site must look modern, clean, and professional, but still realistic for a first-year university web development assignment.

This is not meant to be a full ecommerce website. It should be a **portfolio-style showcase website** that presents featured products, brand identity, contact information, and assignment evidence in a polished way.

The work must clearly reflect lecture content taught across Weeks 1 to 6, including:
- semantic HTML
- CSS Grid
- responsive design
- hamburger navigation
- forms
- hover effects
- transitions / animation
- CSS variables
- correct file structure
- validation-ready code

---

## Assignment Goal
Build a website that can achieve a **distinction-level grade** by meeting the marking criteria strongly in all key categories:
- implementation of pages
- responsive design
- validation and code quality
- site report
- GitHub usage
- video demonstration

---

## Required Pages
Create these 5 pages exactly:

1. `index.html`
2. `project.html`
3. `contact.html`
4. `videoDemo.html`
5. `report.html`

Also create:
- `css/style.css`
- `js/script.js`
- `images/` folder

---

## Website Concept
The website brand is called **GetSauced**.

Theme:
- luxury watches
- premium sneakers
- curated sourced items
- modern dark theme
- clean layout
- high-end visual style

The website should feel like a student-built luxury showcase / portfolio website.

---

## Page Requirements

### 1. index.html
This is the homepage.

Include:
- a hero section with the GetSauced brand name
- a short slogan
- a brief introduction to the brand
- a short paragraph about curated watches and sneakers
- featured category cards or sections
- a call-to-action button linking to the projects page
- at least one large image

Use proper semantic structure:
- `header`
- `nav`
- `main`
- `section`
- `footer`

---

### 2. project.html
This is the featured items / projects page.

This page must demonstrate a **different grid layout** from the rest of the website.

Frame it as:
- Featured Pieces
- Recent Sourced Items
- Watch and Sneaker Collection

Include multiple cards, each with:
- image
- title
- short description
- price / availability text
- placeholder button such as “View Details”

Suggested examples:
- Rolex Datejust
- Rolex Submariner
- Rolex GMT
- Air Jordan 1
- Travis Scott Jordan
- Nike Dunk

Use a CSS Grid layout that is visually different from the other pages.

---

### 3. contact.html
This is the contact / enquiry page.

Include:
- page heading
- short invitation to get in touch
- email/contact information
- a form with:
  - name
  - email
  - subject
  - message
  - submit button

The form should use `mailto:` in the action attribute so it opens the user’s email client.

Use proper form structure with:
- `form`
- `label`
- `input`
- `textarea`

Style the form cleanly and professionally.

---

### 4. videoDemo.html
This page is for the assignment video demonstration.

Include:
- heading
- short explanation of what the demo will show
- placeholder embedded video area using `iframe` or a clear video URL placeholder
- summary of what the video covers:
  - homepage
  - projects page
  - contact page
  - report page
  - responsive design
  - animations
  - CSS concepts

---

### 5. report.html
This page must act like a styled report document.

It must include:
- over 250 words
- reflective discussion of learning web development
- design decisions
- debugging/challenges
- font and colour choices
- websites or designs that influenced the site
- HTML validation screenshot section
- CSS validation screenshot section
- video URL section

This page should be styled like a document:
- wider margins
- strong headings
- readable paragraphs
- clear spacing

---

## Technical Rules

### Semantic HTML
Use the correct HTML tags where appropriate:
- `header`
- `nav`
- `main`
- `section`
- `article`
- `aside`
- `footer`

Do NOT:
- use `<div class="nav">` instead of `<nav>`
- use semantic tags incorrectly
- use deprecated tags like:
  - `<font>`
  - `<center>`
  - `<br>` for layout
  - `<table>` for page layout

Use `div` only as a content container where appropriate, not to replace page-level semantic tags.

---

### HTML Requirements
Every page must include:
```html
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Page Title</title>
  <link rel="stylesheet" href="css/style.css">
  <script src="js/script.js" defer></script>
</head>
<body>
</body>
</html>