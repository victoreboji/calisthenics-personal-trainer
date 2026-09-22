# Calisthenics Trainer Website - HTML Structure Guide

## ✅ HTML Concepts Used (From Your Learning)

### Core Elements
- **HTML Boilerplate**: DOCTYPE, `<html>`, `<head>`, `<body>`
- **Semantic Structure**: `<header>`, `<nav>`, `<section>`, `<footer>`, `<main>`
- **Headings**: `<h1>` (site title), `<h2>` (section titles), `<h3>` (subsections)
- **Text**: `<p>`, `<strong>` (trainer credentials), `<em>` (emphasis)

### Multimedia & SEO
- **Images**: `<img>` with `src` and `alt` attributes
- **Figure/Caption**: `<figure>` + `<figcaption>` for semantic image wrapping
- **Open Graph Meta Tags**: og:title, og:type, og:image, og:url (4 most important)
- **Meta Description**: For SEO page summary

### Navigation & Links
- **Anchor Links**: `<a href="#section-id">` for in-page navigation
- **Address Element**: `<address>` for contact info with links (`<a href="mailto:">` and `<a href="tel:">`)

### Tables (Schedule)
- **Table Structure**: `<table>`, `<thead>`, `<tbody>`, `<tr>`, `<th>`, `<td>`
- **Table Attributes**: `border`, `cellpadding`, `cellspacing`
- **Content**: Day names, time slots (6-7 AM, 2-3 PM, 5-6 PM), availability status

### Forms (Booking & Feedback)
#### Booking Form Elements
- `<form>`, `<label>`, `<input>` (text, email types)
- `<select>` + `<option>` (dropdown for session type, day, time)
- `<button>` (submit button)
- Attributes: `id`, `name`, `placeholder`, `required`

#### Feedback Survey Form Elements
- `<fieldset>` + `<legend>` (group related form controls with labels)
- Radio buttons: `<input type="radio">` (one answer per question)
- Checkboxes: `<input type="checkbox">` (multiple answers)
- `<textarea>` with `rows` and `cols` attributes
- Button types: `type="submit"` and `type="reset"`

## 🎯 File Structure

```
Trainer code/
├── index.html          ← Main website (you are here!)
├── styles.css          ← Ready for styling
├── script.js           ← Ready for interactivity
├── image/              ← Store trainer images
│   └── trainer-hero.jpg (referenced in HTML)
├── audio/              ← For future audio content
└── video/              ← For future video content
```

## 📱 Next Steps (When Ready)

1. **Add CSS Styling**: Create layouts, colors, responsive design
2. **Add JavaScript**: 
   - Form validation and submission
   - Dropdown interactivity
   - Dynamic schedule updates
3. **Optimize Images**: Compress images, use proper formats
4. **Deploy**: Host on GitHub Pages, Netlify, or your own server

## 🔍 SEO Checklist ✅

- ✅ Open Graph tags (4 most important)
- ✅ Meta description
- ✅ Semantic HTML
- ✅ Image alt text
- ✅ Proper heading hierarchy
- ⏳ Mobile responsive (next: CSS)
- ⏳ Fast loading (next: image optimization)

## 💡 HTML Best Practices Applied

- **Semantic HTML**: Using meaningful tags (`<header>`, `<section>`, `<footer>`)
- **Accessibility**: Labels linked to inputs with `for` attribute
- **SEO-Friendly**: Proper meta tags, descriptive alt text, semantic structure
- **Clean Structure**: Logical nesting, proper indentation
- **Attributes Used**: src, alt, href, id, name, type, placeholder, required, rows, cols, etc.
