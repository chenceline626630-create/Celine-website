# Celine's Personal Website — Web Plan

## Vision
A clean, minimalist personal website that functions as a living resume and window into who Celine is — her chemical engineering background, her research and work experiences, and her life as a solo traveler and study-abroad student.

---

## Structure: Multi-Page Site
Each section is its own page. A navigation bar (consistent across all pages) links between them. This makes each section feel focused and distinct, and teaches you how real websites are organized with multiple HTML files.

---

## Pages

### Home (`index.html`)
- Opening visual with name: **Celine Chen**
- One-line tagline: "Engineer by training. Curious by nature. Defined by execution."
- Subtle chemical engineering visual element (minimal molecular line drawing or hexagonal pattern)
- Navigation bar linking to all other pages
- Short welcome paragraph inviting visitors to explore

### About Me (`about.html`)
- Who you are beyond your resume — personality, values, what drives you
- Optional: a professional photo
- 2–3 paragraphs, personal tone

### Education & Research (`education.html`)
- Undergraduate degree + institution
- Study abroad at Case Western Reserve University (CWRU)
- Research projects, lab work, thesis if applicable
- Timeline or card layout

### Work Experience (`work.html`)
- Internships, co-ops, jobs
- Each entry: role, company, dates, 2–3 bullet points
- Card or timeline layout

### Field Notes (`fieldnotes.html`)
- Personal essays or short posts about solo travel, CWRU study abroad, growth
- Start with 1–2 entries; grows over time
- Each entry: title, date, short excerpt — clicking opens a full post page
- Individual posts can be their own HTML files (e.g., `posts/tokyo-2024.html`)

### Contact (`contact.html`)
- Email, LinkedIn, GitHub (if applicable)
- Short "let's connect" message

---

## Design Direction

### Aesthetic: Minimal Science
Clean, precise, and human — like a well-designed lab notebook meets a personal journal.

### Color Palette (proposed)
| Role         | Color              | Hex       |
|--------------|--------------------|-----------|
| Background   | Off-white / ivory  | `#F8F7F4` |
| Primary text | Deep charcoal      | `#2C2C2C` |
| Accent       | Steel teal         | `#4A7C7E` |
| Subtle lines | Light gray         | `#E0E0E0` |
| Highlight    | Warm sand          | `#C9A96E` |

### Typography
- **Headings**: Clean serif (e.g., Playfair Display) — scholarly, thoughtful feel
- **Body**: Modern sans-serif (e.g., Inter or Lato) — easy to read
- **Accents**: Monospace for small labels (dates, section tags) — nods to scientific notation

### Chemical Engineering Visual Elements
- Subtle hexagonal grid or benzene-ring pattern as background texture or dividers
- Thin line molecular structure as a decorative element in the header or footer
- Understated and elegant — no heavy graphics

---

## Tech Stack (learning-friendly)
| Layer      | Tool                        | Why                                    |
|------------|-----------------------------|----------------------------------------|
| Structure  | Plain HTML                  | Fundamentals first                     |
| Styling    | Plain CSS (shared file)     | One stylesheet used across all pages   |
| Behavior   | Minimal vanilla JavaScript  | Mobile nav menu toggle if needed       |
| Fonts      | Google Fonts (free)         | Easy to add, no install needed         |
| Icons      | Font Awesome or SVG icons   | Simple, free                           |
| Hosting    | GitHub Pages                | Free, integrates with your git workflow|

No frameworks (no React, no Bootstrap) until you understand the building blocks.

---

## File Structure
```
Celine-website/
├── index.html          ← Home
├── about.html
├── education.html
├── work.html
├── fieldnotes.html
├── contact.html
├── posts/
│   └── (individual reflection posts)
├── css/
│   └── style.css       ← one shared stylesheet for all pages
└── images/
    └── (photos, graphics)
```

---

## Build Order (section by section)
1. HTML skeleton + shared navigation bar + `style.css` setup
2. Home page (`index.html`)
3. About Me
4. Education & Research
5. Work Experience
6. Reflections index + first post
7. Contact
8. Polish: responsive design (mobile-friendly), hover effects, final styling

---

## Learning Goals Along the Way
- **HTML**: semantic tags, document structure, links, images, multi-page navigation
- **CSS**: box model, flexbox, grid, typography, color, shared stylesheets
- **Git**: commit after each page/section, write good commit messages
- **Responsive design**: media queries so the site looks good on phones too
