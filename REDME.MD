# AppName Landing Page
A simple responsive landing page built with HTML and Tailwind CSS.

# 🚀 AppName — Responsive Landing Page
 
A fully responsive SaaS landing page built with **Tailwind CSS (CDN)** — no custom CSS, no build tools, just utility classes. Created as a learning-friendly demo of mobile-first responsive design using Flexbox and Grid 

No custom `.css` files, no Sass, no CSS frameworks besides Tailwind.
 
## Responsive Breakpoints Used
 
Tailwind is ** mobile-first ** — unprefixed classes apply to * all * screens, and prefixed classes override them from that width upward.
| `sm:`| `md:`| `lg:` | `xl:`| `xl:`
 
##  Sections Breakdown
 
**1. Navigation Bar**
- Sticky (`sticky top-0`) so it stays visible while scrolling.
- Logo left, links center/right, "Get Started" button.
- Links hidden on mobile (`hidden md:flex`); hamburger icon shown instead (`md:hidden`) and toggles a dropdown via JS.
**2. Hero Section**
- Gradient background `bg-gradient-to-br`.
- `flex-col` on mobile  `lg:flex-row` on desktop (text and image side-by-side).
- Responsive heading sizes `text-4xl sm:text-5xl lg:text-6xl`.
- Two CTA buttons that stack on mobile, sit inline from `sm:` up.
- Responsive image height `h-64 md:h-80 lg:h-96` with rounded corners and shadow.
**3. Features Section**
- `grid-cols-1` on mobile → `md:grid-cols-3` on tablet/desktop.
- Three cards (Lightning Fast, Secure, Analytics), each with an icon, title, and description.
- Hover lift effect (hover:shadow-xl hover:-translate-y-1).
**4. Footer**
- Dark background (`bg-gray-900`).
- `flex-col` on mobile → `sm:flex-row` on larger screens.
- Logo on one side, copyright text on the other.
## Learning Notes
  - make and learning  this task to meadia qurary for many screen like 
  mobile , tab , laptop .. , hover set color smooth landind page .. 
## How to Run
No build step needed — it's a static HTML file.
1. Download `index.html`
2. Open it directly in your browser (double click it), or
3. Run a local server, e.g.:
 