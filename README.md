# Web Programming - Lab01: Multi-Page HTML5 Website

## 1. Theme
The project is built around **CloudFlow Systems**, a technical solutions platform focused on DevOps automation, hybrid cloud architecture, and containerized backend infrastructure.

## 2. File Organization
- `index.html`: Home page featuring header navigation, two structured `<article>` tags with images, and footer credentials.
- `about.html`: Architectural overview featuring `<section>`, `<figure>`, `<figcaption>`, and semantic markup (`<aside>`, `<time>`, `<mark>`, `<blockquote>`, `<details>`, `<summary>`).
- `services.html`: Tabular project overview featuring an accessible table structured with `<thead>`, `<tbody>`, and `<tfoot>` across 4 columns and 5 service rows.
- `contact.html`: Consultation form organized using `<fieldset>`, `<legend>`, text/email/date `<input>` elements, a `<select>` dropdown, and a `<textarea>`.
- `assets/`: Directory containing all visual media referenced across pages via relative file paths (`assets/...`).

## 3. Challenges Faced
- **Pure Semantic Layout Without CSS**: Structuring visually readable forms and clean content hierarchy relying strictly on native HTML tags (like `<fieldset>`, `<p>`, `<br>`, and table borders) without any external styling or style blocks.
- **Consistent Relative Navigation**: Ensuring root-relative paths maintain valid references across all pages while conforming to strict semantic HTML nesting constraints.
